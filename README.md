# Next.js Demo Blog
A custom Next.js blog using the blog starter from [sandypockets](https://github.com/sandypockets/nextjs-blog-starter) 



# Local Execution
Run this in your terminal to get started:
```
npm run dev
```
Connect to [http://localhost:3000](http://localhost:3000)

# Dockerfile
Standard commands to build and run the container locally:
```
docker build --tag 'demo-blog-0' .
docker run --rm -it -p 3000:3000 --detach 'demo-blog-0'
```

