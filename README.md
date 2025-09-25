# Web PDF Annotator & OCR Tool

This is a fully client-side web application for viewing, annotating, and extracting text from PDF documents directly in your browser. Built with vanilla JavaScript, it leverages powerful libraries like PDF.js for rendering and Tesseract.js for Optical Character Recognition (OCR).

### Features:

*   **📄 PDF Viewing**: Load and view any PDF file from your local device.
*   **🖍️ Annotation Tools**:
    *   **Pencil**: Freely draw on PDF pages with adjustable brush size.
    *   **Eraser**: Remove annotations with an adjustable eraser size.
*   **🔍 OCR (Optical Character Recognition)**: Select an area on the page to recognize and extract text, which is then copied to your clipboard.
*   **💾 Save & Load Annotations**:
    *   Save all your drawings to a separate `.json` file.
    *   Load your saved annotations back onto the original PDF at a later time.
*   **⚙️ User-Friendly Interface**: Includes a movable and minimizable toolbox, zoom controls, and clear notifications.
*   **🔒 Privacy-Focused**: All file processing happens entirely in your browser. Your documents are never uploaded to a server.
