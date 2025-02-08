# README: Short Title Generator  

## Overview  
The *Short Title Generator* is a script designed to optimize and shorten product or marketing titles while preserving their meaning and relevance. This is particularly useful for platforms with character limits or for improving clarity in listings.  

## Features  
- **Title Length Optimization**: Reduces title length while keeping essential keywords.  
- **Keyword Prioritization**: Retains important terms related to the product.  
- **Stopword Removal**: Eliminates unnecessary words like "the," "and," "with," etc.  
- **Custom Rules**: Allows for specific exclusions or modifications based on business needs.  

## How It Works  
1. The script takes an input title (e.g., `"Wireless Bluetooth Headphones with Noise Cancellation & Mic"`)  
2. It processes the title using:  
   - Predefined keyword importance rules  
   - Synonym replacement (optional)  
   - Stopword and filler word removal  
3. Outputs a shorter, optimized version (e.g., `"Wireless Noise-Canceling Bluetooth Headphones"`)  

## Installation & Usage  
1. Clone the repository or download the script.  
2. Ensure you have Python installed (if applicable).  
3. Run the script with your dataset or individual titles.  

```bash
python short_title.py --input "Original Product Title"
```

## Customization  
- Modify stopword lists in `config.json` or `settings.py`  
- Adjust keyword priority rules in the script  
- Enable or disable certain processing steps  

## Example Use Cases  
✔ E-commerce product listings  
✔ SEO optimization for ads  
✔ Standardizing catalog data  

## License  
This script is open-source and can be modified as needed.  
