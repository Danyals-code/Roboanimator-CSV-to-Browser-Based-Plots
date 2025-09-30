
- `t` → time in seconds  
- `x_m, y_m` → positions in meters  
- `rateR_rpm, rateL_rpm` → wheel speeds in RPM  

The Blender add-on exports files in this format by default.

---

## Notes
- Everything runs locally in your browser; your data is not uploaded anywhere.  
- Works best on desktop with a modern browser (Chrome, Firefox, Edge, Safari).  
- If plots don’t render:
  - Try changing **skiprows** (some files need 1 or 3 instead of 2).  
  - Make sure the CSV includes the required columns.

---

## Development
This project is a single HTML file using:  
- [Plotly.js](https://plotly.com/javascript/) for interactive charts  
- [PapaParse](https://www.papaparse.com/) for CSV parsing  

You can fork or clone the repo, edit `index.html`, and push changes. GitHub Pages will update automatically.
