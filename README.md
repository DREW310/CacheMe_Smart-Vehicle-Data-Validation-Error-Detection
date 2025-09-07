# VehicleVerify Pro - Smart Vehicle Data Validation System

## Solving Malaysian Insurance Application Errors Through AI Pattern Recognition

**Competition Track**: Industry Collaboration

**Team**: CacheMe

**Phase**: Prototype Development

**Live Demo**: https://tofu-hero-35863024.figma.site/

### Problem Statement

The BJAK challenge highlights how vehicle data entry errors delay insurance policy approval and cause pricing problems. Our analysis of the competition dataset revealed that only 47 out of 200 Malaysian insurance applications were completely error-free, creating a 76.5% error rate that represents significant operational challenges.

Common error patterns include brand typos like "Toyot" instead of "Toyota," model mistakes like "Civicy" instead of "Civic," impossible years like 1800 or 2099, and license plate format issues missing proper Malaysian spacing. These patterns are predictable and systematic, making them ideal candidates for intelligent validation solutions.

### Our Creative Solution

VehicleVerify Pro introduces culturally-aware validation that understands how Malaysian users actually make mistakes. Unlike generic form validators that only check basic formats, our system recognizes reversed spellings like "audoreP" for "Perodua" and character substitutions like "T0y0ta" for "Toyota."

The innovation lies in combining pattern recognition with educational feedback. Instead of displaying generic error messages, our system explains Malaysian vehicle registration standards while providing intelligent suggestions based on actual user behavior patterns from the competition dataset.

Key creative features include fuzzy string matching with Malaysian brand familiarity weighting, reversed text detection algorithms, and smart year inference based on actual vehicle production timelines rather than arbitrary date ranges.

### Technical Feasibility

Our technology choices balance sophisticated capabilities with realistic implementation. React with TypeScript provides modern frontend development using frameworks taught in university curricula. Node.js with Express offers reliable backend services with extensive documentation and community support. Python with scikit-learn delivers proven machine learning capabilities within established academic frameworks.

Each team member contributes specialized expertise that aligns with AI degree coursework. The machine learning specialist implements pattern recognition using established scikit-learn methods. The frontend developer creates validation interfaces using React principles. The backend developer manages API services and database integration. The data analyst processes the competition dataset to extract validation rules.

### Prototype Demonstration

Our Figma prototype showcases complete validation scenarios based on competition dataset error patterns. Users can interact with realistic demonstrations including brand name intelligence that suggests "Toyota" when typing "Toyot," model validation that corrects "Civicy" to "Civic," year validation that flags impossible dates, and automatic license plate formatting.

The demonstration emphasizes educational feedback and cultural sensitivity, showing how the system builds user trust through transparency about suggestion reliability and confidence scoring.

**Live Interactive Demo**: https://tofu-hero-35863024.figma.site/
