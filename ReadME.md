# 🎯 Visual Product Matcher

A full-stack **AI-powered product search engine** that allows users to **upload an image or paste an image URL** and instantly find visually similar products using **OpenAI’s CLIP model**.  

Built with:
- ⚡ **Backend:** Node.js + Express.js + Python (PyTorch + CLIP)
- 🎨 **Frontend:** React + Vite
- 📦 **Embeddings:** CLIP (ViT-B/32) + cosine similarity
- 🗄 **Data storage:** JSON-based product catalog + embeddings index

---

## 🚀 Features

- 🔍 **Visual Product Search:** Upload an image or paste a URL to search products by similarity.  
- 🎨 **Preview System:** Instant preview of uploaded image/URL.  
- 🛍 **Add New Products:** Add products with name, category, and image URL.  
- ⚡ **Automatic Index Rebuild:** New products are added to `products.json` and embeddings are automatically rebuilt for immediate availability.  
- 📊 **Configurable Search:** Adjust number of results (Top-K) and minimum similarity score threshold.  
- 🖼 **Cached Image Downloads:** Product images cached locally for efficiency.  
- 🖥 **Clean UI:** Modern React UI with responsive design and Tailwind-inspired CSS theme.  

---

## 🏗️ Project Structure

