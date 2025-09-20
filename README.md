## License
This project is licensed under the MIT License.

## Credits
This project is forked from [bchiang7](https://github.com/bchiang7/v4)
Original work by [Brittany Chang].

## 🛠 Installation & Set Up



1. Delete the Existing cache

   ```sh
   rmdir /s /q node_modules
   rmdir /s /q public
   rmdir /s /q .cache
   del package-lock.json
   ```

2. Commit the Changes if any

   ```sh
   git add .
   git commit -m "Describe your changes" --no-verify
   git push
   ```

3. Install npm and gh-pages to host on github

   ```sh
   npm install -- --legacy-peer-deps
   npm install gh-pages --save-dev --legacy-peer-deps
   ```

4. Build

   ```sh
   npm run build -- --prefix-paths
   ```

5. Deploy

   ```sh
   npm run deploy -- --legacy-peer-deps
   ```
