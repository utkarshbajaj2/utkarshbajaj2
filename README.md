<img width="1400" height="350" alt="image" src="https://github.com/user-attachments/assets/1d85e62a-89ba-496a-a243-dba09885249f" />


Full Stack Engineer, contributing my expertise in TCS .
Strong communicator with a confident and convincing approach.

Experience in building web apps using Angular v14+ & Spring Boot . Proficient in Java, REST APIs and Spring Security. Solid grasp of RxJS, & Material UI integration. Familiar with tools like VS Code, Eclipse, and Git. 

Happy to connect — let’s network, work, and if the vibe’s right, take it offline over something stronger than deadlines.


Built scalable web apps with Angular v14+ and Spring Boot. Strong in Java 8, REST APIs, Angular, and RxJS. Sharp eye for cloud related technologoy and UX with a grip on design psychology. Hands-on with VS Code, Eclipse, Git, WinSCP, weblogic Console 12C , Jenkins etc. Clear communicator, confident, and naturally convincing .


💼 Experience 
Tata Consultancy Services (TCS)
🧑‍💻 Full Stack Dev – Angular + Spring Boot




🔧 Debugged 50+ “mystery issues” 🕵️‍♂️ — boosted uptime by 30% (AKA: fewer 3 AM calls).
🛡 Fixed MPT security flaws so well even hackers got bored 😎.
📦 Built 15+ shiny new features, from infinite scroll to file uploads—because users always want more.
🎤 AGM 2025 Platform: Supported 10,000+ shareholders without the app crashing (miracle? maybe).
🧼 Migrated Angular from v14 to v19 in 1 day—yes, one. day. Zero UI breakage. Take that, tech debt.
♿ Made apps compliant with the RPwD Act. Because accessibility ≠ optional.
🧱 Worked with DevOps to slap security headers on like sunscreen—because XSS & CSRF? No thanks.



🎓 Academic Shenanigans
🎓 B.Tech (Honors) – Computer Science
📍 Oriental Institute of Science & Tech, RGPV University, Bhopal
📅 Oct 2020 – Jun 2024 | 📈 CGPA: 8.02 (because 8.03 was too mainstream)



from PIL import Image, ImageDraw, ImageFont
import matplotlib.pyplot as plt

# Define badge information (text, background color)
badges = [
    ("JavaScript", "#F7DF1E"), ("Java", "#ED8B00"), ("Python", "#3776AB"),
    ("HTML", "#E34F26"), ("CSS", "#1572B6"), ("Next.js", "#000000"),
    ("React", "#61DAFB"), ("Node.js", "#339933"), ("Bootstrap", "#7952B3"),
    ("TailwindCSS", "#06B6D4"), ("MongoDB", "#47A248"), ("PostgreSQL", "#336791"),
    ("Docker", "#2496ED"), ("GitHub", "#181717")
]

# Image settings
badge_width = 200
badge_height = 50
padding = 10
cols = 5
rows = -(-len(badges) // cols)
image_width = badge_width * cols + padding * (cols + 1)
image_height = badge_height * rows + padding * (rows + 1)

# Create a new image
img = Image.new("RGB", (image_width, image_height), "black")
draw = ImageDraw.Draw(img)

# Load a font
try:
    font = ImageFont.truetype("arial.ttf", 20)
except IOError:
    font = ImageFont.load_default()

# Draw badges
for i, (text, color) in enumerate(badges):
    col = i % cols
    row = i // cols
    x = padding + col * (badge_width + padding)
    y = padding + row * (badge_height + padding)
    draw.rectangle([x, y, x + badge_width, y + badge_height], fill=color)
    w, h = draw.textsize(text, font=font)
    draw.text((x + (badge_width - w) / 2, y + (badge_height - h) / 2), text, fill="white", font=font)

# Show the image
plt.figure(figsize=(12, 6))
plt.imshow(img)
plt.axis('off')
plt.tight_layout()
plt.show()




🛠 Skills
Frontend:
HTML5, CSS3, SCSS, JavaScript, Angular v14–19, Material UI, RxJS

Backend:
Java 8, Spring Boot, Spring Security, Servlets

Database:
Oracle SQL Developer Tools

Tools & Platforms:
VS Code, Eclipse, Git, GitLab, Postman, WinSCP, Jenkins, WebLogic Console 12c

Cloud & Concepts:
Azure Fundamentals, REST APIs, OOPs, Basic DSA, Accessibility (RPwD Act), DevOps Collabs



📜 Certifications (AKA “Paper That Proves I Know Stuff”)
Microsoft Certified: Azure Fundamentals (AZ-900)

Java Programming Course Certification

Certified in Java EE Application Servers

Git Version Control Course





<img width="300" height="285" alt="image" src="https://github.com/user-attachments/assets/c81fc03c-cbbc-4811-8642-0f357e94372b" />




