Campus Study Space Finder
The Campus Study Space Finder is a web application designed to help students locate and check the availability of study spaces across campus in real-time. This tool aims to solve the common problem of students wandering around campus looking for a place to study, especially during peak hours and exam periods.
Call for Contributors: Campus Building Maps
We are currently seeking contributions from developers to create individual layout maps for various study locations across campus. These maps will be integrated into our Leaflet.js-based interface to provide students with clear visual representations of each study space.
What We Need;
We need detailed 2D bird's eye view layout maps for the following campus buildings:

Main Library (all 5 floors)
Student Union Building
Science & Engineering Complex
Arts & Humanities Center
Business School
Campus Center
Residence Hall Study Lounges

Technical Requirements

Maps should be created as SVG files for easy integration with our map system
Follow the established color scheme:

Walls/Boundaries: #333333
Study Desks/Tables: #4285F4
Group Study Rooms: #34A853
Computer Stations: #EA4335
Quiet Zones: #FBBC05


Include clear indicators for:

Entry/exit points
Restrooms
Elevators/Stairs
Power outlets
Vending/Café areas


Keep file sizes optimized (under 200KB per map if possible)
Use clear naming conventions for all elements (for future interaction capabilities)

Getting Started

Fork this repository
Choose a building from the unassigned list (update the Projects board when you start)
Create your map in your preferred SVG editor (Figma, Adobe Illustrator, Inkscape)
Place completed SVG files in the /src/assets/maps/ directory
Update the building metadata in buildings.json with your map information
Submit a pull request with your contribution

Design Resources

Basic templates are available in the /design/templates/ directory
Campus building floor plans can be found in /resources/floor-plans/
Example implementation can be seen in /examples/library-1st-floor.svg

Integration Plans
Your maps will be integrated with our interactive system that will:

Highlight available study spaces in real-time
Allow students to click on specific areas for detailed information
Show amenities and features for each space
Provide filtering options for space type, noise level, and amenities

Questions?
If you have questions or need clarification, please:

Open an issue with the tag "map-question"
Contact the project lead at champoclive7@gmail.com

Thank you for helping make campus study space hunting easier for everyone!
