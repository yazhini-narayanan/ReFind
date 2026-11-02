# ReFind
A smart campus lost-and-found system that automatically matches lost and found items using descriptions, colors, categories, locations, and dates.
# Campus Lost & Found Matcher

### An Automated Lost-and-Found Matching System for College Campuses

##  About the Project

Campus Lost & Found Matcher is a web-based application designed to help students find their lost belongings more easily.

In college campuses, students often report lost and found items through different WhatsApp groups, notice boards, or directly to other students. As a result, people who find lost items may never come across the original owner's report.

Our project aims to solve this problem by automatically comparing lost-item and found-item reports and identifying potential matches.

##  Objectives

- Simplify the process of reporting lost and found items.
- Automatically identify similar lost and found reports.
- Rank potential matches based on their similarity.
- Reduce the time and effort required to reunite students with their belongings.

##  How It Works

1. Students submit a lost-item or found-item report.
2. The system collects details such as:
   - Item name and category
   - Colour
   - Description
   - Location
   - Date
3. A matching algorithm compares new reports with existing reports.
4. Potential matches are ranked based on their similarity scores.
5. The system displays likely matches for verification.

##  Example

**Lost Report:**

- Item: Scientific Calculator
- Colour: Black
- Location: Near Physics Lab

**Found Report:**

- Item: Calculator
- Colour: Dark Grey
- Location: Outside Laboratory 2

The system identifies these reports as a potential match based on their similar descriptions and locations.

## Technologies Used

- Python – Core programming and matching algorithm
- Streamlit – Web application interface
- SQLite / CSV – Data storage
- GitHub – Version control and collaboration

## Success Measurement

The system will be tested using 50 sample lost and found reports. Its performance will be evaluated based on how accurately it identifies genuine potential matches.

## Team

Developed as a student hackathon project.

##  Project Status

Currently under development.
