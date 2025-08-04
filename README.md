# Cars 2017 Narrative Visualization (Martini Glass Structure)

This project is an **interactive narrative visualization** built with **D3.js**.  
It tells the story of fuel efficiency in 2017 cars using a **Martini Glass narrative structure**:
- **Three author-driven scenes** guide the user through key insights.
- **The final scene unlocks interactivity**, allowing exploration through filtering and tooltips.

The project uses:
- D3.js for rendering
- d3-annotation for annotations
- GitHub Pages for hosting

---

## How to Run

1. Clone this repository.
2. Open `index.html` in a browser (or serve via a local server).
3. Navigate through scenes using the **Next** and **Previous** buttons.
4. In the final scene:
   - Hover over points to see detailed car information.
   - Use the dropdown to filter by fuel type.

---

# Essay

## **Messaging**

The visualization communicates:
- How 2017 car models differ in **fuel efficiency (MPG)**.
- The **role of fuel type** (Gasoline, Diesel, Electric) in MPG performance.
- How **4-cylinder cars and electric vehicles** stand out for efficiency.

The main message:
> *Fuel type and engine design strongly influence fuel efficiency, with electric and 4-cylinder cars achieving the highest MPG.*

---

## **Narrative Structure**

This visualization follows a **Martini Glass structure**.

- **Author-driven section:**  
  The first three scenes are linear. The user cannot interact except to move forward/backward.
- **Reader-driven section:**  
  In the final scene, the user can:
  - Hover for details
  - Filter by fuel type
  - Explore patterns on their own

This design corresponds exactly to the **martini glass model** described in class, where exploration only happens at the end.

---

## **Visual Structure**

- **Consistent visualization across all scenes**
