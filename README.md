# Live Google Docs Blog

Code repo for Jordan Ford & David Carter design blog on tech, design, and futurism
Building in public 2025

<!--
## ✅ Features

- **Live Editing View** — As you update the document, viewers see changes instantly
- **Google Docs Styling** — Mimics the Docs interface with a lightweight fake toolbar
- **Easy Hosting** — Deploy with GitHub Pages, Vercel, or Netlify
- **Minimal Setup** — Just update one line with your document ID

## 🛠 Setup

1. **Publish your Google Doc**
   - Go to your Google Doc
   - Click `File > Share > Publish to web` or set sharing to "Anyone with the link"
   - Copy the document ID from the URL (it's the long string between /d/ and /edit)

2. **Update the Document ID**
   - Open `index.html`
   - Replace `YOUR_DOCUMENT_ID_HERE` with your actual Google Doc ID
   - The line should look like: `<iframe src="https://docs.google.com/document/d/your-actual-doc-id/edit?usp=sharing"`

3. **Deploy**
   - Upload the files to your preferred hosting service
   - For GitHub Pages:
     - Create a new repository
     - Upload the files
     - Enable GitHub Pages in repository settings

## 🔒 Security Notes

- Make sure your Google Doc is set to "Anyone with the link can view"
- The embedded document will be read-only for visitors
- You can still edit the document through Google Docs directly
-->

## 🎨 Customization

You can customize the appearance by modifying the CSS in the `<style>` section of `index.html`:

- Change colors in the `.fake-toolbar` class
- Adjust the toolbar height by modifying the `iframe-wrapper` height calculation
- Update the font family in the `html, body` selector

## 📝 License

MIT License - feel free to use this for your own projects!
