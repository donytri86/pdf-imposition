# PDF Imposition Tool

A free, browser-based PDF imposition tool for creating N-up layouts with customizable settings. Perfect for printing multiple pages on a single sheet while maintaining vector quality.

## Features

- **N-Up Layout** - Arrange multiple PDF pages on a single sheet (2-up, 4-up, 8-up, 16-up, etc.)
- **Vector Quality** - Maintains perfect PDF vector quality, no blurriness or pixelation
- **Customizable Grid** - Configure any column × row layout (e.g., 2×4, 3×3, 4×2)
- **Adjustable Spacing** - Set custom gutters between pages and margins around the sheet
- **Flexible Scaling** - Fit to width or use original page size
- **Multi-page Output** - Automatically generates multiple sheets for large documents
- **Live Preview** - See your layout before downloading
- **Client-Side Processing** - All processing happens in your browser, no file uploads to servers

## Use Cases

- **Printing Efficiency** - Print multiple pages per sheet to save paper and ink
- **Booklet Creation** - Create booklets, zines, or pamphlets
- **Sticker Sheets** - Arrange labels or stickers in a grid layout
- **Business Cards** - Print multiple business cards on a single sheet
- **Thumbnail Sheets** - Create contact sheets or thumbnail overviews
- **Cost Reduction** - Reduce printing costs by fitting more content per page

## How to Use

1. **Upload PDF** - Click "Upload PDF" and select your PDF file
2. **Configure Layout**
   - Set the number of columns and rows
   - Adjust gutters (spacing between pages)
   - Set sheet dimensions and margins
   - Choose scaling mode
3. **Generate** - Click "Generate Imposition" to create the layout
4. **Download** - Click "Download Result" to save your imposed PDF

## Settings Explained

### Preprocessor
- **Scale Mode**: Choose between "Fit to Width" or "Original Size"
- **Target Width**: Desired width for each page (in mm) when using "Fit to Width"

### N-Up Layout
- **Columns**: Number of pages horizontally
- **Rows**: Number of pages vertically
- **Gutter X/Y**: Spacing between pages (set to 0 for no gaps)

### Sheet Settings
- **Width/Height**: Output sheet dimensions in millimeters (A4 = 297×210mm)
- **Margins**: Top, right, bottom, left margins around the content area

### Content Alignment
- **Horizontal**: Left, Center, or Right alignment
- **Vertical**: Top, Center, or Bottom alignment

## Technical Details

### Technologies Used
- **PDF.js** - For rendering PDF previews
- **pdf-lib** - For vector-quality PDF manipulation
- **Tailwind CSS** - For responsive UI design
- **Vanilla JavaScript** - No framework dependencies

### Browser Compatibility
Works in all modern browsers that support:
- ES6+ JavaScript
- HTML5 Canvas
- File API

### Privacy & Security
- 100% client-side processing
- No files uploaded to any server
- No data collection or tracking
- Works completely offline once loaded

## Installation

No installation required! Simply open `index.html` in a web browser.

## Examples

### Common Layouts
- **2-Up** (2×1): Two pages side by side
- **4-Up** (2×2): Four pages in a 2×2 grid
- **8-Up** (2×4 or 4×2): Eight pages per sheet
- **16-Up** (4×4): Sixteen pages per sheet

### Standard Paper Sizes
- **A4**: 297mm × 210mm (landscape) or 210mm × 297mm (portrait)
- **Letter**: 279mm × 216mm (landscape) or 216mm × 279mm (portrait)
- **Legal**: 356mm × 216mm (landscape) or 216mm × 356mm (portrait)
- **A3**: 420mm × 297mm (landscape) or 297mm × 420mm (portrait)

## Tips for Best Results

1. **No Gaps**: Set gutters and margins to 0 for edge-to-edge page placement
2. **Even Distribution**: Ensure your layout fits well with your sheet size
3. **Vector Quality**: The tool preserves vector graphics, fonts, and text
4. **Batch Processing**: Perfect for processing 100+ page documents
5. **Print Settings**: When printing, disable any "fit to page" options in your print dialog

## Keywords

PDF imposition, N-up printing, PDF layout tool, print multiple pages per sheet, PDF grid layout, booklet maker, PDF arranger, page imposition, PDF tile, sheet layout, printing optimization, paper saver, PDF merger, page layout tool, vector PDF, PDF manipulation, browser PDF tool, online PDF imposition, free imposition software, PDF utility

## License

MIT License - Free to use, modify, and distribute

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## Support

If you find this tool useful, please star the repository on GitHub!

---

Made with ❤️ for the printing and design community
