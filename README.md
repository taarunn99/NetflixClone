# 🎬 Netflix Clone | React + TypeScript 

Its a fully functional **movie streaming platform** that mimics the UI and experience of **Netflix**. 🎥  
It fetches movie and TV data using the **TMDB API**, providing a sleek and responsive interface with features like **custom hooks, infinite scrolling, portals, lazy loading, and more!** 🚀  

## 🔧 Tech Stack  
- **React** → Component-based UI  
- **Redux Toolkit (RTK)** → State management  
- **MUI (Material UI)** → UI components and theming  
- **Video.js** → Seamless video playback  

## 🔹 Key Features  
- 🎥 **Movie & TV Show Streaming** → Fetches real-time data from TMDB  
- 📌 **Infinite Scrolling** → Uses Intersection Observer API  
- 🌀 **Lazy Loading & Suspense** → Efficient code-splitting with React Router  
- 🎭 **Custom Hooks & HOC** → Reusable logic for optimized performance  
- 🎨 **MUI Theming** → Fully customizable design  
- ⚡ **RTK Query** → Optimized API data fetching  

### **🚀 Run with Docker**  
```sh
docker build --build-arg TMDB_V3_API_KEY=your_api_key_here -t netflix-clone .
docker run --name netflix-clone-website --rm -d -p 80:80 netflix-clone
