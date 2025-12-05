# landy-app

Geolandy_prototype Description

Geolandy_prototype is a web application developed in Python using Streamlit that allows users to check whether a property is affected by the Reserva Forestal Protectora Bosque Oriental de Bogotá (Eastern Forest Protective Reserve of Bogotá).
The system performs automatic geospatial analyses and generates detailed PDF reports.

Problem it Solves

Property owners, investors, and real estate professionals need to know whether a property has environmental restrictions that could limit its use.
Geolandy automates this process, which traditionally required:

✅ Manual inquiries across multiple government agencies
✅ Specialized geospatial analysis
✅ Interpretation of environmental regulations
✅ Preparation of technical reports

✨ Features
🔍 Search Options

Search by CHIP: Direct lookup using the property’s cadastral code

Search by Coordinates: Locate a property using X, Y coordinates (EPSG:3116) (in progress)

Format validation: Automatically checks the CHIP format

📊 Geospatial Analysis

Intersection calculation: Detects which areas of a property overlap with protected zones

Impact percentages: Calculates affected and unaffected areas

Categorical classification: Preservation, Restoration, Sustainable Use, Public Use, Environmental Recovery

Interactive maps: Visualization with Folium, color-coded by category

📄 PDF Reports

Comprehensive report: Includes executive summary, maps, and regulatory details

Two maps: Property detail + general location within the reserve

Applicable regulations: Lists permitted and prohibited activities per zone

Professional layout: Ready for institutional presentation