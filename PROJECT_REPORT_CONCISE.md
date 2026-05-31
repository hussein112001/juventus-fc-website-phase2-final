# Juventus FC Website - Phase 2 Project Report
## CSCI390: Web Programming | Spring 2025-2026

---

### 1. Project Overview
*   **Student Name**: Hussein Khalaf
*   **Course**: CSCI390 - Web Programming
*   **Project Title**: Juventus FC Official Fan Portal
*   **Submission Date**: May 31, 2026
*   **GitHub Repository**: [https://github.com/hussein112001/juventus-fc-website-phase2-final](https://github.com/hussein112001/juventus-fc-website-phase2-final)
*   **Live Website**: [https://hussein112001.github.io/juventus-fc-website-phase2-final/](https://hussein112001.github.io/juventus-fc-website-phase2-final/)

---

### 2. Executive Summary
This project represents the Phase 2 evolution of the Juventus FC web portal. Transitioning from a static HTML structure to a modern **ReactJS** application, the project implements a component-based architecture, responsive design, and professional UI/UX standards. The application features 5 core pages: Home, About, Squad, Trophies, and Contact.

---

### 3. System Design & Technologies
The system is built using a modern frontend stack designed for performance and scalability:

*   **Core Framework**: React 19 with TypeScript for type-safe development.
*   **Styling Engine**: Tailwind CSS 4 for rapid, utility-first UI development.
*   **Routing**: Wouter for lightweight, client-side navigation.
*   **UI Components**: shadcn/ui for accessible, professional-grade interface elements.

#### Technology Stack Breakdown:
| Category | Technology |
| :--- | :--- |
| **Frontend** | React 19, TypeScript |
| **Styling** | Tailwind CSS 4, Lucide Icons |
| **Build Tool** | Vite |
| **Deployment** | GitHub Pages |

---

### 4. Key Implementation Features
*   **Responsive Architecture**: Fully optimized for Mobile, Tablet, and Desktop using Tailwind's flexible grid system.
*   **Branding**: Strict adherence to Juventus FC brand guidelines (Black, White, and Gold color palette).
*   **Dynamic Components**: Modular React components for Squad profiles, Trophy showcases, and History timelines.
*   **Interactive Forms**: Validated contact form with real-time feedback using toast notifications.

---

### 5. Code Snippets
#### 5.1 Main Routing Structure
```typescript
export default function App() {
  return (
    <div className="min-h-screen bg-background flex flex-col">
      <Navigation />
      <main className="flex-grow">
        <Switch>
          <Route path="/" component={Home} />
          <Route path="/about" component={About} />
          <Route path="/squad" component={Squad} />
          <Route path="/trophies" component={Trophies} />
          <Route path="/contact" component={Contact} />
          <Route component={NotFound} />
        </Switch>
      </main>
      <Footer />
    </div>
  );
}
```

---

### 6. Conclusion
The Phase 2 implementation successfully achieves all project objectives, demonstrating a high level of proficiency in modern web development practices. The resulting application is a production-ready, responsive, and visually compelling fan portal for Juventus FC.
