# MIST4610-Project2-Group1

## Team Name and Members:
Group 1
  1. Vashishtha, Ayush [@avash1015](https://github.com/avash1015)
  2. Challa, Amruta [@amrutac921](https://github.com/amrutac921)
  3. Machado Mota, Felipe [@FelipeMachadoMota](https://github.com/FelipeMachadoMota)
  4. Gujjula, Nikhilesh [@nikhileshgu](https://github.com/nikhileshgu)
  5. Mai, Elvis [@elviskietmai](https://github.com/elviskietmai)

## The Data:
The dataset, obtained from the Los Angeles Open Data portal, contains over a million records across 28 columns, detailing crime incidents in the Los Angeles area. Each row represents a single crime, with categorical information such as the area name, crime description, and premises description, alongside quantitative data like the date and time of occurrence, geographic coordinates, and victim age, offering a comprehensive view of crime patterns for prospective residents.

## Dataset Questions:
Based on the data, we created a scenario: "A family with young children plans to move to the Los Angeles area. Along with job location and school ratings, the parents look at what kind of crimes occur most often and where the most crime occurs."

  1. Between male and female victims, what is the most common age that have been involved in a crime? Which gender has the higher victim rate? 
  2. What are the 5 most dangerous areas where crimes have been committed? 

The team's questions directly tackle a relocating family's main worries: safety and where crime happens. First, they want to know the most common age of male and female crime victims and which gender is more often a victim. This helps understand who is most at risk. Second, they want to find the five most dangerous neighborhoods. This is key for deciding where to live and how to stay safe. Both questions use the dataset's information about victims' ages and genders, and the names of the areas where crimes occurred, so we can use the data to find the answers.

## Question One:
<img width="700" alt="Screenshot 2025-04-28 at 5 30 40 PM" src="https://github.com/user-attachments/assets/ee5050d0-c9aa-405d-aa84-74c54ff71448" />

**Analysis:**
The line chart displays the number of crimes in Los Angeles categorized by victim age and sex. Both male (M, orange line) and female (F, blue line) victims show a similar trend: crime involvement increases sharply from a young age, peaks in the late 20s to mid-30s, and then gradually declines with age. Notably, there appears to be a slightly higher number of male victims compared to female victims across most age groups, particularly around the peak crime ages. There are also some smaller spikes and dips in crime numbers at specific ages, suggesting potential variations in the patterns.

**Manipulation:**
To analyze crime victim demographics by age and gender, the dataset was filtered to remove incomplete entries (no nulls/no “x”) for victim age and sex. Then, victim age was placed on the x-axis, and a count of crimes was placed on the y-axis to visualize the frequency of crimes at each age. Finally, victim sex was used to color-code the lines on the line chart, allowing for a direct visual comparison of crime trends between male and female victims across different age groups

## Question Two:
<img width="700" alt="Screenshot 2025-04-28 at 5 30 31 PM" src="https://github.com/user-attachments/assets/cbc9e74b-88dc-4198-a85c-721881f8758a" />

**Analysis:**
This map pinpoints the top five Los Angeles areas with the highest crime rates, using color intensity to represent the volume of reported incidents. Central stands out with the darkest red, indicating the highest concentration of crime among these hotspots. Following Central, 77th Street, and Pacific also exhibit substantial crime levels with moderately dark red hues. While Southwest and Hollywood show lighter shades, signifying a comparatively lower crime count within this high-crime group, they still represent areas with significant criminal activity. For a relocating family, this visualization immediately flags Central, 77th Street, and Pacific as areas requiring careful consideration and further investigation into the specific types of crimes occurring, while also highlighting that even the relatively "safer" areas within this top five still warrant thorough scrutiny.

**Manipulation:**
To visualize the top five areas with the highest crime rates, the dataset was filtered to focus on these specific "Area Name" entries. The average longitude and latitude for each of these areas were then used to position them geographically on a map. To clearly differentiate these areas by crime volume, the "Count" of crimes was applied to the color, using a gradient where darker shades of red indicate a higher number of reported crimes. The "Area Name" was added as a label for each point on the map. This visualization effectively displays the geographic locations of the top five high-crime areas and visually communicates the relative number of crimes in each through color intensity.

## Tableau Packaged Workbook
[Download the Tableau Workbook](MIST4610-Project2-Group1.twbx)
