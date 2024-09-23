# 代写 MECH4305 PROBLEM SET 1

**Date**: 2024-09-22 00:00:00

Fourier Analysis and Convolution

**Due date**:
5pm Friday Week 3 (September 27)

**Submission instructions**:
Submit your problem sets on Moodle by the due date using the template provided. In your submissions, you will need to show FULL working (handwritten or typed), state any assumptions, and include any discussion, figures, and a copy of any MATLAB Code.

**Question 1**:
Sojourner landed on Mars in 1997 as part of the Pathfinder mission and was the first rover to operate on a planet other than Earth. Prior to its deployment, vibration testing was performed at the Jet Propulsion Laboratory (JPL) Environmental Test Laboratory to determine whether Sojourner could withstand the expected dynamic forces it would encounter during its mission.
The rover can be modelled as the single degree-of-freedom system shown in Figure 1, with a mass of 11.5 kg and equivalent stiffness of 126 N/m. During the first phase of testing, Sojourner was subjected to the repeated forces (which are periodic for all t) shown in Figure 2, where one period of each force is given.

**Figure 1**.

For each force (Force A & B, separately), complete the following:
a) Derive the Fourier series representation of the force.
b) Plot the original force (as shown in Figure 2) against your Fourier series representation of the force from t = -20 to 20 s with n = 100 terms.
c) Starting with the equation of motion for the system shown in Figure 1, derive the steady state response of the rover.
d) Plot the steady state response of the rover from t = 0 to 20 s with n = 100 terms.
e) If displacement amplitudes of > 20 mm damage onboard equipment, does the applied force present a problem? Use your response plotted in d) and answer in a sentence or two.

= 0
(t )
(t )
2
Copyright UNSW Sydney

**Figure 2**. One period of Force A, () and Force B, ().

**Question 2**:
In the second phase of testing, the rover (see Figure 1) was subjected to the non-periodic forces in Figure 3.

For each force (Force A & B, separately), complete the following:
a) Derive the response of the rover using the convolution integral.
b) Find the response using a numerical integrator such as MATLAB’s ode45 and compare the integral and numerical solutions on a plot for t = 0 to 10 s.
c) Damping material is now added to the rover to influence its vibrational response. Repeat the numerical solution in b) (there is no need to calculate another convolution integral) with a damping constant ζ = 0.25. Compare the undamped and damped response on a plot for t = 0 to 10 s.
d) In a sentence or two, describe the effect of damping on the response.

() = {
, − ≤ ≤ 0
2, 0 ≤ ≤
where = 2
() = {
0, − ≤ ≤ 0
cos(), 0 ≤ ≤
where =
3
Copyright UNSW Sydney

**Figure 3**. Non - periodic Force A, () and Force B, ().

**Question 3**:
“We do not learn from experience. We learn from reflecting on experience” (attributed to John Dewey, Educator and Philosopher)
Reflective writing gives you an opportunity to think about what you've learned so far and the relationship between this course and the acquisition of knowledge for your future career. I want you to consider the link between theory (what you study in class) and practice (the application of the theory in the real world).

Reflecting on your experiences in this course over the first 3 weeks, write a reflection (approx. ½ page in length) that addresses the following questions:
• What have you learned so far and why is it important?
• How much did you know about the subject before we started?
• What do you think is the link between industry practice and this course?
• What have you found to be clear / unclear, easy / difficult, interesting / surprising / unexciting, and why?
• How will you enhance your learning in this course moving forward?

() = {
0, ≤ 0
−4, > 0
() = {
0, ≤ 0
+ sin⁡(10), > 0
4
Copyright UNSW Sydney

**Reflection Marking Rubric**:
Criteria/Mark 1 2 3
Describing Experience Unclear and vague. Clear but general. Clear and focused on the specific aspects that challenge or interest the student.
Reflection Minimal reflection - No personal reflection or discussion is limited to description of general opinions. Connections are not drawn between class content and personal experience and/or industry practice. Some reflection - Connects class content/activities with personal experience or industry experience but remains superficial. Limited/superficial insight about self or a particular issue. Critical reflection – Demonstrates superior connections between class content/activities, personal experience and/or industry practice. Articulates new understanding/insights about self or particular issue/concept.
Writing Quality Unfocused, unorganized, vague, and sloppy. May feature many grammatical or spelling errors. Some focus and organization. Language has some precision. Reflection was proofread. Discussion is clear and specific; descriptions use concrete and precise language and insights are precise and clear. Organization is apparent and effective. Reflection has been proofread for grammar, punctuation, and spelling errors.
# MECH4305 matlab

# CS Tutor | 计算机编程辅导 | Code Help | Programming Help

# WeChat: cstutorcs

# Email: tutorcs@163.com

# QQ: 749389476

# 非中介, 直接联系程序员本人
