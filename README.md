# InvoiceFlow Pro

A modern, professional web-based invoice generator built with vanilla HTML, CSS, and JavaScript. Create beautiful invoices with real-time preview, PDF export, and print functionality.

## ✨ Features

### Professional Design
- Clean, minimalist interface with modern gradient design
- Two-panel layout: input form and live preview
- Fully responsive design (desktop, tablet, mobile)
- Smooth animations and professional typography

### Invoice Management
- **Company Details**: Logo, name, address, email, phone, tax ID
- **Client Information**: Name, address, email
- **Invoice Metadata**: Auto-generated invoice numbers, issue date, due date
- **Dynamic Line Items**: Add/remove items with automatic calculations
- **Real-time Calculations**: Subtotal, tax, discount, and grand total

### Export & Print
- **PDF Export**: High-quality PDF generation using html2pdf.js
- **Print Support**: Browser-optimized printing
- **Save Templates**: Store company details for reuse
- **New Invoice**: Quick reset with auto-incremented numbers

## 🚀 Quick Start

### Option 1: Direct Use
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start creating invoices immediately!

### Option 2: GitHub Pages
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Access your invoice generator at `https://yourusername.github.io/invoiceflow-pro`

### Option 3: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/invoiceflow-pro.git

# Navigate to directory
cd invoiceflow-pro

# Open with any local server (example with Python)
python -m http.server 8000

# Visit http://localhost:8000
```

## 📋 How to Use

1. **Setup Company Details**
   - Fill in your company information in the first section
   - Add your logo URL (optional)
   - Click "Save Template" to store for future use

2. **Add Client Information**
   - Enter client details for each invoice
   - Information appears instantly in the preview

3. **Create Line Items**
   - Click "Add Item" to add invoice items
   - Enter description, quantity, and unit price
   - Totals calculate automatically

4. **Set Taxes & Discounts**
   - Add tax rate as percentage
   - Apply discount amount
   - Watch totals update in real-time

5. **Export Your Invoice**
   - Click "Generate PDF" to download
   - Use "Print Invoice" for direct printing
   - "New Invoice" to start fresh

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic structure
- **Tailwind CSS**: Modern utility-first styling
- **Vanilla JavaScript**: No frameworks, maximum compatibility
- **html2pdf.js**: Client-side PDF generation
- **Boxicons**: Professional icon set
- **Inter Font**: Modern typography

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### No Dependencies Required
- Single HTML file contains everything
- All libraries loaded via CDN
- No build process or installation needed

## 📁 File Structure

```
invoiceflow-pro/
├── index.html          # Complete application (single file)
└── README.md           # This file
```

## 🎨 Customization

The application uses Tailwind CSS classes for styling. To customize:

1. **Colors**: Modify the gradient classes in the HTML
2. **Typography**: Update font family in the style section
3. **Layout**: Adjust Tailwind grid and spacing classes
4. **Branding**: Replace logo and company details

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📞 Support

If you encounter any issues or have questions:
- Open an issue on GitHub
- Check existing issues for solutions
- Review the code comments for implementation details

## 🌟 Features in Detail

### Real-time Preview
- Instant updates as you type
- Professional invoice layout
- Print-ready formatting

### PDF Export
- High-quality PDF generation
- Maintains formatting and styling
- Excludes form elements from export

### Template System
- Save company details locally
- Quick setup for recurring clients
- Browser localStorage integration

### Responsive Design
- Mobile-first approach
- Touch-friendly interface
- Consistent experience across devices

---

**Made with ❤️ for small businesses and freelancers**

*InvoiceFlow Pro - Professional invoicing made simple*
