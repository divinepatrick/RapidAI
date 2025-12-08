# Rapid AI
## This tool leverages Clipdrop - for image generation, Gemini ai - for text generation, Cloudinary for image edits
# Clone and Setup
* This web app is built using Next.js React, expressjs... therefore, you'll need to have ```node.js``` installed in your local machine.

* After successfully installing ```node```, clone the repository into your machine using the command below: </br>
```bash 
git clone https://github.com/divinepatrick/rapidai.git
```
This will clone the whole repository into your local machine.

- To install all required dependencies to your sytem, navigate to the directory where your cloned repository lives and execute:
```node
npm install
```
- Now create a ```.env``` file in both client and server directories```./client``` and ```./server```.
#### In ```./client``` directory, add the following to your ```.env```
- ```VITE_CLERK_PUBLISHABLE_KEY=YOUR_PUBLISHABLE_KEY```
get this from ```clerk```. For this, you'll need a [clerk](https://clerk.com/) account.
- ```VITE_BASE_URL=http://localhost:3000``` 

#### In ```./client``` directory, add the following to your ```.env```
- ```DATABASE_URL=YOUR_NEONDB_URL``` get this from [neon](https://console.neon.tech/)

- ```CLERK_PUBLISHABLE_KEY=pk_YOUR_CLERK_PUBLISHABLE_KEY```

- ```CLERK_SECRET_KEY=sk_YOUR_CLERK_SECRET_KEY```

- ```GEMINI_API_KEY=YOUR_GEMINI_API_KEY``` for text generation

- ```CLIPDROP_API_KEY=YOUR_CLIPDROP_API_KEY``` for image generation

- ```CLOUDINARY_CLOUD_NAME=YOUR_CLOUDINARY_CLOUD_NAME``` from [cloudinary](https://console.cloudinary.com/app/)

- ```CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY```

- ```CLOUDINARY_API_SECRET=YOUR_CLOUDINARY_API_SECRET```

# Technologies used

### ```UI```
- Clerk for Auth
- ReactJS
- Lucide icons
- Prebuiltui

### ```SERVER ```
- express
- dotenv
- cors
- axios
- cloudinary
- multer
- clipdrop - for image generation
- gemini ai - text generation
- cloudinary to remove image background and image object
- pdf-parse
- react-hot-toast

# See what I'm up to on 🔎

- [LinkedIn](https://linkedin.com/in/divinepatrick)