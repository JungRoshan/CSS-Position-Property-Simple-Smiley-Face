# CSS-Position-Property-Simple-Smiley-Face
Focused on different CSS position values and created a simple smiley face using positioned elements.

🔧 What I Practiced
Created four demo sections showing the effect of different CSS position values on elements.

Used top and left properties to offset positioned elements and observe their behavior.

Built a circular emoji face with eyes and mouth using CSS with absolute positioning for facial features.

Applied border-radius to create circles and rounded shapes.

Positioned elements relative to their containers and viewport to understand layout flow and stacking.

📄 HTML & CSS Highlights
Positioning Demo:

Four sections each containing two divs: one default green box and one yellow box with different position values (static, relative, absolute, fixed).

Used fixed height and width for boxes, with borders and margins for spacing.

Demonstrated how static ignores top and left, relative offsets from original position without removing from flow, absolute positions relative to nearest positioned ancestor or viewport, and fixed stays fixed relative to viewport even on scroll.

Emoji Face:

A 400x400px orange circular div (#emoji) as the face.

Two black circular eyes (#left-eye, #right-eye) absolutely positioned inside the face.

A brown mouth with rounded bottom corners, absolutely positioned below the eyes.

Used position: absolute for facial features to precisely place them inside the face container.

🧠 Key Takeaways
position: static is the default and does not respond to offset properties.

position: relative moves the element relative to its normal position, preserving original space.

position: absolute removes the element from document flow and positions it relative to the nearest positioned ancestor or the viewport.

position: fixed fixes the element relative to the viewport, keeping it visible during scroll.

Combining border-radius and position properties enables creation of complex shapes and layouts like emoji faces.

Understanding positioning is crucial for advanced layout control and interactive UI design.

