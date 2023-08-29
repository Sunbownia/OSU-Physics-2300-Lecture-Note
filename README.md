# Physics 2300 - Intermediate Classical Mechanics: Lecture Notes

## Purpose of This Document

This document has been created by students to provide fellow learners of the Physics 2300 course at The Ohio State University with a concise and structured set of notes derived from the lecture content.

- **Quick Reference:** Students can quickly search keywords through the document to recall specific concepts.
 
- **Structural Clarity:** This document adopts the Markdown format, which clearly distinguishes key points and phased summaries of each lecture video, making it easy to navigate.
 
- **Study Aid:** Before tests or exams, this summary can serve as a quick revision tool, ensuring students cover all major points.

We advise students to treat this document as a complementary tool. While it covers the main points of the lecture, in-depth explanations, examples, and intonations from the lecturer, Professor Michael Lisa, can only be fully experienced by watching the lecture videos. Remember, Physics is not just about memorizing formulas and concepts but understanding the intricate beauty and logic that govern our universe. Dive deep, ask questions, and most importantly, enjoy the journey of learning!

*All contents within this document were compiled and organized by students while watching the professor's lecture videos. We appreciate any help to improve our documents. We're looking forward to your input!*

## Copyright and Disclaimer Notice 

This document is a compilation and synthesis created exclusively by students and derived from the lecture videos of Professor Michael Lisa. The copyrights and ownership rights to the content herein belong solely to the students who contributed to this document. The primary intent of this document is to serve as a supplementary resource for students enrolled in the Physics 2300 course at The Ohio State University.

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
- The $n$ th term is characterized as $\frac{x^n}{n!}$ multiplied by the $n$ th derivative of $f$.

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


## Extra: Dipole-Dipole Force

### Overview

In this extra session, we explore the force between two electric dipoles and examine its scaling properties. We'll focus on the case where the size of each dipole $a$ is much smaller than the distance $D$ separating the two dipoles.

---

### Defining the Problem

- **Dipole**: A pair of charges (positive and negative) separated by a distance $a$.
- **Coulomb Force**: Force between point charges, scales as $ \frac{1}{r^2} $.

Consider two dipoles:
1. Dipole A consists of charges 1 and 2.
2. Dipole B consists of charges 3 and 4.

Goal: Find the scaling behavior of the force between dipoles A and B.

---

### Setting Up the Equation

Using Coulomb's Law, the force between individual charges can be described. The force on dipole A due to B is a sum of forces between corresponding charges.

- **Force between 1 & 3**: $ F_{1,3} = -\frac{k Q^2}{D^2} $
- **Force between 1 & 4**: $ F_{1,4} = \frac{k Q^2}{(D+a)^2} $
- **Force between 2 & 3**: $ F_{2,3} = \frac{k Q^2}{(D-a)^2} $
- **Force between 2 & 4**: $ F_{2,4} = -\frac{k Q^2}{D^2} $

Summing these forces:

$$
F_{A,B} = kQ^2 \left( -\frac{2}{D^2} + \frac{1}{(D+a)^2} + \frac{1}{(D-a)^2} \right)
$$

Factor out $ \frac{1}{D^2} $:

$$
F_{A,B} = kQ^2 \left( \frac{1}{D^2} \right) \left( -2 + \frac{D^2}{(D+a)^2} + \frac{D^2}{(D-a)^2} \right)
$$

Let $ x = \frac{a}{D} $, we are interested in $ x \ll 1 $.

---

### Approximation Using Taylor Series

For $ x \ll 1 $, we can expand the function $ f(x) $ as:

$$
f(x) = f(0) + f'(0)x + \frac{1}{2}f''(0)x^2 + \ldots
$$

In our case:
- $ f(0) = 0 $
- $ f'(0) = 0 $
- $ f''(0) = 12 $

We find the force $ F_{A,B} $ scales as:

$$
F_{A,B} \approx 6kQ^2 \left( \frac{a^2}{D^4} \right)
$$

**Key Insight**: The force between two dipoles scales as $ \frac{1}{D^4} $.

---

### Conclusion

- To lowest order, the force between two dipoles scales as $ \frac{1}{D^4} $.
- This conclusion is particularly relevant when the size of the dipole $a$ is much smaller than the distance $D$ between them.

---

### Active Review

- We started by understanding the nature of a dipole and setting up equations based on Coulomb's law.
- We used a Taylor Series approximation to find how the force between two dipoles scales with distance.
- The force scales as $ \frac{1}{D^4} $, which is an important result for many applications in physics and chemistry.

By following these steps, you can similarly approach problems that require approximations and scaling behavior.

## Lecture 2-1: Physics Statics Basics

### Overview
In this lecture, we discuss the fundamental principles of physics statics. We'll cover the laws that govern static objects and introduce the four primary forces encountered in this domain: gravity, tension, normal forces, and friction. The lecture emphasizes applying these simple laws to increasingly complex real-world situations.

---

### What is Statics?
- **Definition**: Statics is the study of objects that are not in motion, i.e., velocity and angular velocity are zero.
- **Newton's Laws**: 
  - $$ F = ma \quad (\text{Force is mass times acceleration}) $$
  - $$ \tau = I \alpha \quad (\text{Torque is moment of inertia times angular acceleration}) $$

---

### Four Fundamental Forces in Statics

#### Gravity
- **Newton's Law of Gravity**: 
  - $$ F = \frac{{G \times m_1 \times m_2}}{{r^2}} \times \hat{r} $$
- **Weight**: 
  - $$ W = mg \quad (\text{Weight is mass times gravitational acceleration}) $$

#### Tension
- **Definition**: Tension is the pulling force transmitted along the length of a string, wire, or rod.
- **Tension Variability**: Tension may vary along the string, especially if the string has mass.

#### Normal Force
- **Definition**: The normal force is the force exerted by an object that supports another object resting on it. It acts perpendicular to the surface.
  
#### Friction
- **Types**: 
  - **Static Friction**: Prevents relative motion between surfaces.
  - **Kinetic Friction**: Opposes relative motion between surfaces.
- **Static Friction Formula**: 
  - $$ F_{\text{max}} = \mu N \quad (\text{Max force before sliding starts}) $$

---

### Newton's Third Law and Free Body Diagrams
- **Third Law**: Every action has an equal and opposite reaction.
- **Free Body Diagrams**: Use separate diagrams for each object involved in the problem.

---

### Questions & Anomalies
- **Why is static friction not constant?**: Static friction varies depending on the applied force, up to a maximum limit defined by $ F_{\text{max}} $.

---

### Conclusion
Physics statics explores the behavior of stationary objects through the interplay of forces such as gravity, tension, normal forces, and friction. Understanding Newton's laws and knowing how to draw Free Body Diagrams are essential for tackling complex problems in statics.

---

### Active Review
- Recall Newton's laws and how they apply to static scenarios.
- Familiarize yourself with the four key forces: gravity, tension, normal forces, and friction.
- Understand the importance of Newton's third law and separate Free Body Diagrams in problem-solving.

## Lecture 2-2: Comprehensive Analysis of Morin

### Overview

Today's session dives deep into Problems 2.3.5 and 2.6 from Morin's book. The aim is to gain a thorough understanding of forces and motion through the study of two mechanical systems involving tension, normal force, and friction.

---

### Setting Up Both Problems

#### Morin 1: Sticks & Strings on a Frictionless Surface

- **Problem Description**: Two sticks are on a frictionless surface, connected by a hinge at the top and a string at the bottom.
- **Key Geometry**: 
  - Angles: $ \alpha = 90^{\circ} - \theta $ 
  - $ \alpha + \theta = 90^{\circ} $

#### Morin 2: Tension, Normal Force, and Friction

- **Static Situation**: All forces are in equilibrium.
- **Massless String**: Tension (T) remains constant along the string in static cases.

---

### Free Body Diagrams and Forces

#### Morin 1: Right & Left Stick

- **Forces for Each Stick**: 
  - Weight downward
  - Normal force upward
  - Tension $ T_{R/L} $
  - Hinge forces $ \pm H_x $ and $ \pm H_y $

#### Morin 2: Infinitesimal Rope Element

- **Forces**: 
  - Tension $ T $
  - Normal force $ dN $
  - Friction $ df $

---

### Equations of Motion and Analysis

#### Morin 1:

1. **Horizontal Forces for Left Stick**: $ T_{Lx} - H_x = 0 $
2. **Vertical Forces for Left Stick**: $ N_L + T_{Ly} - H_y - mg = 0 $
3. **Torque for Left Stick**: $ T_{Lx} \times L - mg \times L - N_L \times L = 0 $

#### Morin 2:

1. **Tension**: Upward force = $2T$, Downward force = $mg$
2. **Normal Force**: $ dN = T \times d\phi $
3. **Friction**: $ df = \mu \times dN $

**Key Insight: Dimensionality**
- Tension varies with angle $ \phi $ due to the friction force acting along the rope's length.

---

### Strategies for Solving Equations & Insights

#### Morin 1:

- **5 Equations, 5 Unknowns**: $ T, H_x, H_y, N_L, N_R $
  - Solve for $ N_L $ using equation 3.
  - Substitute $ N_L $ into equation 2 to find $ H_y $.
  - Use $ H_y $ in equation 5 to solve for $ T $.

#### Morin 2:

- **Tension Varies**: It varies with the angle $ \phi $ due to the friction force acting along the rope's length.

---

### Conclusion

- **Free Body Diagrams** are the backbone for analyzing mechanical systems.
- **Geometry and Dimensionality** play a critical role in simplifying equations and understanding variable forces like tension.

---

### Questions & Anomalies

- **For Morin 1**: Why did we use multiple Free Body Diagrams?
- **For Morin 2**: What happens to the system if the tension varies recursively due to friction?
### Answers to Questions & Anomalies

#### For Morin 1: Why did we use multiple Free Body Diagrams?

- **Clarity**: Each stick has different forces acting upon it, requiring its own diagram to isolate those forces.
- **Precision**: Analyzing each stick separately helps to identify individual forces, making it easier to formulate equations of motion.
- **Simplification**: With separate diagrams, you can tackle each equation independently before combining them to find the solution.

#### For Morin 2: What happens to the system if the tension varies recursively due to friction?

- **Non-Linearity**: The tension no longer remains a constant value throughout the rope. This adds a level of complexity to solving equations of motion.
- **Dimensionality Insight**: As the angle $ \phi $ changes, so does the normal force $ dN $ and hence the friction $ df $, causing a recursive change in tension $ T $.
- **System Instability**: If the tension changes recursively in a way that exceeds the frictional capacity of the system, the rope may slip or the system could become unstable.

---

### Active Review

- We used multiple Free Body Diagrams in Morin 1 for clearer analysis, precise force identification, and simpler equation formulation.
- In Morin 2, the dimensionality played a significant role in understanding how tension varies recursively due to the friction force, adding complexity to the system.
---

### Active Review

- How did geometry and free body diagrams simplify the equations for Morin 1?
- What role did dimensionality play in understanding tension variations in Morin 2?

---
