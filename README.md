# ZenVision

# Smart Glasses for Discreet ADHD Support

ZenVision is a wearable smart glasses system designed to support children with ADHD who struggle with impulsive verbal outbursts in the classroom. Built for a 9-year-old child, Megan, introduced to us by our clients, the system discreetly detects when she speaks out loudly—often a response to anxiety—and gently delivers visual reminders on the lens to help with self-regulation, without singling her out.

The system uses an ESP32 microcontroller and MAX4466 microphone to monitor sound in real-time. A custom CNN (built with TensorFlow and trained on MFCCs) confirms whether the voice is Megan’s before triggering the prompt—achieving an average response time of just 1.93 seconds. A companion web dashboard (HTML/CSS/JS + Plotly.js) logs these events to a real-time database, enabling teachers and parents to track behavioral patterns and progress over time.

**Achievements:** 
Selected as a Top 20 Project (out of 187 teams) in the UofT ESP (APS 112) Showcase.
