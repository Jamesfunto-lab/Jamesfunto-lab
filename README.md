- 👋 Hi, I’m @Jamesfunto-lab
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Jamesfunto-lab/Jamesfunto-lab is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import { SiteHeader } from "@/components/site-header"
import { Card, CardContent, CardHeader, CardTitle } from "@/components/ui/card"
import Image from "next/image"

// Mock project data (in a real app, this would come from a database or API)
const projects = [
  {
    id: "1",
    title: "E-commerce Redesign",
    client: "Fashion Retailer",
    role: "UX Designer",
    duration: "3 months",
    challenge: "The client wanted to redesign their outdated website to improve user engagement and conversions. They also wanted a more modern, mobile-responsive design.",
    approach: [
      "Conducted user research through interviews, surveys, and analytics reviews.",
      "Performed a competitive analysis to benchmark the user experience.",
      "Created low-fidelity wireframes to map out the user flow.",
      "Developed interactive prototypes to test with users and gather feedback.",
      "Designed high-fidelity mockups based on feedback.",
      "Conducted usability tests with key stakeholders and iterated the design.",
    ],
    solution: "The final product was a sleek, modern website that improved the conversion rate by 20% and significantly enhanced the mobile user experience.",
    results: [
      "Increased User Engagement: User engagement increased by 30% within the first month.",
      "Improved User Satisfaction: Customer satisfaction scores improved by 25%.",
      "Positive Client Feedback: 'The new design has transformed our online presence and significantly boosted our sales.' - Client CEO",
    ],
    
