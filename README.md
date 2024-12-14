# Next.js & Cloudinary example app

This example shows how to create an image gallery site using Next.js, [Cloudinary](https://cloudinary.com), and [Tailwind](https://tailwindcss.com).

## Usage

1. Get your Environment Variables
2. Import a Zerops project with 
```yml
project:
  name: Image Gallery
  
services:
  - hostname: app
    type: nodejs@20
    envSecrets:
      CLOUDINARY_API_KEY: get-from-cloudinary
      CLOUDINARY_API_SECRET: get-from-cloudinary
      CLOUDINARY_FOLDER: get-from-cloudinary # create a folder in cloudinary from media explorer
      NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME: get-from-cloudinary
```
3. Setup zerops.yml
4. Go to Zerops Dashboard and connect your repository with Github integration and trigger at activation.


## References

- Cloudinary API: https://cloudinary.com/documentation/transformation_reference
