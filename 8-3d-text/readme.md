
``` bash
# Install dependencies (only the first time)
npm install

# Run the local server at localhost:8080
npm run dev

# Build for production in the dist/ directory
npm run build
```
## Deployment
Project deployed using vercel cli
added ```"deploy": "vercel --prod"``` to scripts inside package.json file and changed output dir to ```dist``` during setup
