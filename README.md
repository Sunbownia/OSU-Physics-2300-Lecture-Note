# Physics 2300 - Intermediate Classical Mechanics: Lecture Notes

## Purpose of This Document

This document has been created by students to provide fellow learners of the Physics 2300 course at The Ohio State University with a concise and structured set of notes derived from the lecture content.

- **Quick Reference:** Students can quickly search keywords through the document to recall specific concepts.
 
- **Structural Clarity:** This document adopts the Markdown format, which clearly distinguishes key points and phased summaries of each lecture video, making it easy to navigate.
 
- **Study Aid:** Before tests or exams, this summary can serve as a quick revision tool, ensuring students cover all major points.

We advise students to treat this document as a complementary tool. While it covers the main points of the lecture, in-depth explanations, examples, and intonations from the lecturer, Professor Michael Lisa, can only be fully experienced by watching the lecture videos. Remember, Physics is not just about memorizing formulas and concepts but understanding the intricate beauty and logic that govern our universe. Dive deep, ask questions, and most importantly, enjoy the journey of learning!

*All contents within this document were compiled and organized by students while watching the professor's lecture videos. We appreciate any help to improve our documents. We're looking forward to your input!*

## Copyright and Disclaimer Notice 

This document is a compilation and synthesis created exclusively by students and derived from the lecture videos of Professor Michael Lisa. The original insights, interpretations, and structure of the notes are the work of the students who wrote them. The copyrights and ownership rights to the content herein belong solely to the students who compiled this document. The primary intent of this document is to serve as a supplementary resource for students enrolled in the Physics 2300 course at The Ohio State University.

Any individual or entity who believes their rights have been infringed upon or that there's a breach of intellectual property within this document is encouraged to make immediate contact with the compiler. Upon validation of such claims, we commit to taking prompt action, including, but not limited to, the removal of all contested content.

## Lecture 1-1: Vectors

### Overview

Vectors are crucial mathematical entities used to describe quantities with both magnitude and direction. In contrast, scalars, like mass, are mere numbers without direction. Our class will frequently use vectors to represent physical quantities such as force, velocity, and position.

### Notations and Symbols

- **Vector Notation:** A vector is often represented with an arrow over the symbol. For instance, force is written as $\vec{F}$.
- **Magnitude:** It signifies the size of the vector and is shown with absolute value brackets, e.g., $|F| = 20\,\text{Newtons}$.
- **Direction:** Defined in relation to the horizontal and vertical axes, using a coordinate system of X and Y.

### Components of Vectors

A vector can be decomposed into its components along the X, Y, and sometimes Z axes. Using trigonometry, we can represent them as:
- $F_x = |F| \cos \theta$
- $F_y = |F| \sin \theta$
- $F_z = |F| \cos(90 - \theta)$ (an alternative expression)

### Representation of Vectors

- **Triplets:** A vector can be represented as a triplet, such as $(F_x, F_y, F_z)$.
- **Unit Vector Notation:** A vector can also be written using the unit vectors $\mathbf{i}$, $\mathbf{j}$, and $\mathbf{k}$, like $5\,\text{Newtons} \, \mathbf{i} - 2\,\text{Newtons} \, \mathbf{j} + 6\,\text{Newtons} \, \mathbf{k}$.

### Some Essential Formulas

- **Magnitude from Components:** Using the Pythagorean theorem, the magnitude can be calculated as $\sqrt{F_x^2 + F_y^2 + F_z^2}$.
- **Angle from Components:** The angle $\theta$ can be found using inverse tangent, $\tan^{-1}\left(\frac{F_y}{F_x}\right)$.

### Conclusion

Vectors are indispensable in representing quantities with both magnitude and direction. Understanding their properties, notations, and operations will be invaluable as we progress in our studies.

## Lecture 1-2: Units

### Overview

Units guide us in the vast realm of physical equations, helping us steer our intuition, verify results, and even construct formulas.

### The Range Equation: A Prelude

Imagine a ball, with mass $m$, projected at an angle $θ$ with an initial velocity $v$. Its trajectory, due to Earth's gravitational pull, is parabolic. The gravitational acceleration, $g$, points downward and is approximately $9.8 m/s^2$. Notably, in this class, when referencing $g$, we mean its magnitude, a positive number.

### The Fundamental Units in Mechanics

Three units serve as our primary building blocks in mechanics:

- **Mass (M):** Measured in kilograms (kg).
- **Length (L):** Typically in meters (m).
- **Time (T):** Seconds (s).

For electrical phenomena, the charge, denoted as $q$, uses the unit coulomb.

### Units of Angles

Angles in physics, specifically radians, are dimensionless. Consider a circle: the angle $θ$ is the arc length divided by the radius. Both measurements use length units, making their ratio unitless. Thus, when stating an angle is one radian, it means the arc length equals the radius.

### Crafting Formulas with Dimensional Analysis

For our ball, its range $R$ can depend on its mass, gravitational constant, initial velocity, and the angle of projection. Dimensional analysis derives the relationship:

$$R \sim v^2/g$$

This formula reveals that the ball’s mass doesn’t affect its range in a vacuum.

### Oscillations and Springs

Consider a spring holding a mass. Pull it down, and when released, it oscillates. The oscillation frequency, $f$, might depend on:

- Gravitational constant
- Mass
- Spring constant $k$
- Displacement $x$

From Newton's second law, the spring constant $k$ has units of mass divided by time squared $(kg/s^2)$.

Dimensional analysis can provide a relationship for the frequency of the spring’s oscillations. However, without complete analysis, the exact relation remains unknown.

### Conclusion

Dimensional analysis is the compass of physics. By studying units, we gain profound insights, making it an essential tool for both new and experienced physicists. Whether uncovering quantum field secrets or playing with a spring, remember: the universe speaks the language of mathematics, with units as its grammar.

## Lecture 1-3: Taylor Expansion

### Overview

Today, we delve deep into the realm of the Taylor Series, a mathematical powerhouse that will frequently grace the pages of this course, particularly in Chapter One.


### What is the Taylor Series?

Imagine observing a system proximate to a specific reference point—perhaps it's an equilibrium or a distinct time, $t = 0$. We utilize a variable, say $x$, to measure the deviation from this reference. The smaller $x$ becomes, the nearer we approach our reference point.

Every system under study has an associated function, $f$, which changes with $x$. When $x$ approaches zero, $f$ is similarly approximate to zero. Yet, the intricacies of nature aren’t always straightforward. The Taylor Series breaks this approximation into progressive corrections, refining our comprehension of $f$ with each step.


### Breaking Down the Series

The Taylor Expansion elucidates these corrections as:

$$
f(x) \approx f(0) + x \times f'(0) + \frac{x^2}{2!} \times f''(0) + \frac{x^3}{3!} \times f'''(0) + \dots
$$

Where:
- $f'(0)$, $f''(0)$, etc., signify the first, second, and subsequent derivatives of $f$ when $x = 0$.
- The $n$ th term is characterized as $\frac{x^n}{n!}$ multiplied by the $n$th derivative of $f$.

### A Key Insight: Dimensionality

If $x$ is dimensional (like length), juxtaposing terms such as $x$ and $x^2$ isn’t direct. For example, if $x = 10$ millimeters, then $x^2 = 100$ millimeter-squared—quantities that appear incomparable. Equating dimensions as diverse as a room's length and its area doesn’t render tangible insights.

This challenge suggests that while Taylor Series shine brightest with dimensionless parameters, they can efficiently handle dimensional quantities too.

### A Glimpse into Einstein's Energy Formula

Venturing into Einstein's energy formula for particles, he posited:

$$
E = \frac{mc^2}{\sqrt{1 - \frac{v^2}{c^2}}}
$$

Where:
- $c$ represents the speed of light.
- $m$ denotes mass.
- $v$ is the particle's velocity.

Introducing $\beta = \frac{v}{c}$ and expanding around small velocities (non-relativistic limit), Einstein shed light on energy behaviors at speeds dwarfed by light:

$$
E = mc^2 (1 + \frac{1}{2} \beta^2 + \dots)
$$

Here:
- $mc^2$ epitomizes the rest energy of an inert particle.
- $\frac{1}{2} m v^2$ is the quintessential kinetic energy we recognize from classical physics.
- Successive terms are the relativistic corrections—virtually negligible unless speeds approach light's velocity.

### Why Didn’t Newton Notice the Corrections?

Newton's oversight of these minute corrections wasn't due to neglect. Even for particles zipping at 10,000 miles per hour, these relativistic nuances remain minuscule, evading detection without advanced instruments.


### Conclusion

The Taylor Series stands as a formidable ally in physics and broader applied sciences. By simplifying intricate functions into digestible, accessible components near chosen focal points, it unfurls a world of deeper understanding and insight.
