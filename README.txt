CLOTHING STORE CATALOG MANAGEMENT
=================================

Folder structure
  clothing-catalog/
    backend/   (server.js, package.json, data/products.json)
    frontend/  (index.html, style.css, app.js)
    java/      (ClothingStoreCatalog.java)

A) Web version (Node.js needed: check with "node -v")
  1. cd backend
  2. npm install
  3. npm start
  4. Open http://localhost:3000

B) Java version (Java 17+ needed: check with "java -version")
  1. cd java
  2. javac ClothingStoreCatalog.java
  3. java ClothingStoreCatalog

Note: the file inside backend/data must be named products.json (with an s).
