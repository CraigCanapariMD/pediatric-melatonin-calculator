# Pediatric Melatonin Dosing Calculator

[![License: CC BY-NC 4.0][image-1]][1]

A free, open-source, evidence-based melatonin dosing calculator for children. Built for parents, pediatricians, and sleep consultants.

<img width="520" height="949" alt="melatonin_calculator_screenshot" src="https://github.com/user-attachments/assets/b2fe4f12-9de4-446d-8ade-bf86d8a38223" />

## Features

- **Age-based dosing** for children 2+ years based on 2025 IPSA consensus guidelines
- **ASD support** with guidance for children with autism spectrum disorder
- **Safety warnings** including overdose risk awareness and storage reminders
- **Side effect guidance** to help identify when doses are too high
- **Mobile responsive** design
- **No dependencies** — single HTML file, works anywhere

## Live Demo

[Try the calculator][2] on Dr. Canapari's website.

## Usage

### Option 1: Embed directly

Copy the contents of `calculator.html` into any webpage. The calculator is self-contained with inline CSS and JavaScript.

### Option 2: WordPress

1. Create a new page in WordPress
2. Add a "Custom HTML" block (or Kadence HTML block)
3. Paste the contents of `calculator.html`
4. Publish

### Option 3: Link to hosted version

Feel free to link to the hosted version at drcraigcanapari.com.

## Customization

### Colors

Edit the CSS variables at the top of the file:

```css
:root {
    --primary-color: #1E73BE;
    --primary-hover: #165B9A;
    /* ... */
}
```

### Fonts

The calculator uses Google Fonts (Libre Baskerville and Nunito Sans). Replace these in the `<link>` tag and CSS if desired.

### Links

Update the internal links to point to your own resources:
- Overdose information link
- Sleep training link

## Medical Disclaimer

This calculator provides general guidance only. Melatonin should be used only with the recommendation of and supervision from a medical provider. The information provided is not a substitute for professional medical advice, diagnosis, or treatment.

## Evidence Base

Dosing recommendations are based on:

1. **Owens J, et al.** IPSA Expert Consensus Recommendations for Healthcare Providers. *Sleep Medicine*. 2025;128:127-129.

2. **Bruni O, et al.** Current role of melatonin in pediatric neurology: Clinical recommendations. *European Journal of Paediatric Neurology*. 2015;19(2):122-133.

3. **Edemann-Callesen H, et al.** Use of melatonin in children and adolescents with idiopathic chronic insomnia. *EClinicalMedicine*. 2023;61:102048.

4. **Williams Buckley A, et al.** Practice guideline: Treatment for insomnia and disrupted sleep behavior in children and adolescents with autism spectrum disorder. *Neurology*. 2020;94(9):392-404.

## Key Recommendations

### For Typically Developing Children

| Age           | Maximum Dose    |
| ------------- | --------------- |
| Under 2 years | Not recommended |
| 2–3 years     | 1 mg            |
| 4–5 years     | 2 mg            |
| 6–10 years    | 3 mg            |
| 11+ years     | 5 mg            |

- **Starting dose:** 0.5 mg
- **Timing:** 30–60 minutes before desired bedtime
- **Titration:** Increase by no more than 1 mg per week

### For Children with ASD

- Start with the same doses as typically developing children
- If ineffective at age-appropriate maximum, may increase up to 10 mg total daily (all formulations combined)
- **Physician supervision is essential** when exceeding standard doses

### Important Principles

- Behavioral interventions should precede and accompany melatonin use
- Intermittent use is preferred over daily use
- Store safely out of reach of children
- Use USP-verified products

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

### Ideas for contribution:
- Translations to other languages
- Accessibility improvements
- Additional calculator features (e.g., chronobiotic dosing for DSPD)
- Integration examples for other platforms

## License

**Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**

This means:
- ✅ Free for personal, academic, and nonprofit use
- ✅ Must include attribution to Craig Canapari, MD
- ❌ Commercial use requires a separate paid license

See [LICENSE][3] for full details.

## Citation

If you use this calculator in academic work, please cite:

```
Canapari, C. (2025). Pediatric Melatonin Dosing Calculator [Computer software]. 
https://github.com/CraigCanapariMD/pediatric-melatonin-calculator
```

**BibTeX:**
```bibtex
@software{canapari2025melatonin,
  author = {Canapari, Craig},
  title = {Pediatric Melatonin Dosing Calculator},
  year = {2025},
  url = {https://github.com/[YOUR_USERNAME]/pediatric-melatonin-calculator},
  note = {Based on 2025 IPSA consensus guidelines}
}
```

## Commercial Use

For commercial licensing inquiries (healthcare companies, apps, hospital systems), please contact via [drcraigcanapari.com/speaking-and-consulting][4].

## Author

**Craig Canapari, MD**  
Director, Yale Pediatric Sleep Center  
Associate Professor, Yale School of Medicine  
[drcraigcanapari.com][5]

## Acknowledgments

- International Pediatric Sleep Association (IPSA) for the 2025 consensus guidelines
- American Academy of Neurology for ASD practice guidelines

[1]:	https://creativecommons.org/licenses/by-nc/4.0/
[2]:	https://drcraigcanapari.com/melatonin-dosing-calculator/
[3]:	LICENSE
[4]:	https://drcraigcanapari.com/speaking-and-consulting/
[5]:	https://drcraigcanapari.com

[image-1]:	https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
[image-2]:	screenshot.png
