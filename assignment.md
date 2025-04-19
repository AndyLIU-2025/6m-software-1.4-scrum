## Assignment

### Brief

Write your answers for each question:

Question 1:
Imagine you are hired by a startup company for a school to implement their IT infrastructure as their IT consultant. n your own words (300 words or less), describe how could implementing Scrum help their IT team improve their productivity.

Answer:

# How Implementing Scrum Can Improve a Startup IT Team's Productivity  

Implementing Scrum can significantly enhance a startup IT team’s productivity by fostering adaptability, collaboration, and efficiency. Here’s how:  

1. **Iterative Progress**  
   Scrum divides projects into 2-4 week sprints, delivering incremental value. This allows the team to adapt quickly to evolving startup needs, test ideas early, and reduce risks of long-term misalignment.  

2. **Clear Priorities**  
   The Product Owner maintains a prioritized backlog, ensuring the team focuses on high-impact tasks first. This minimizes wasted effort on low-value work, critical for resource-constrained startups.  

3. **Daily Accountability**  
   Daily stand-ups promote transparency, enabling rapid issue resolution and alignment. In fast-paced environments, this prevents bottlenecks and keeps momentum.  

4. **Structured Feedback**  
   Sprint reviews and retrospectives ensure continuous stakeholder input and process refinement. Startups can pivot swiftly based on feedback, while the team iteratively improves workflows.  

5. **Defined Roles**  
   Scrum Masters remove roadblocks, freeing developers to focus on execution. Self-organizing teams foster ownership and innovation, leveraging startup agility without chaos.  

6. **Reduced Ambiguity**  
   Fixed roles, ceremonies, and artifacts (e.g., sprint goals) create clarity, minimizing miscommunication—common in unstructured environments.  

By embedding flexibility, accountability, and continuous improvement, Scrum helps startups streamline IT infrastructure development, accelerate delivery, and maintain alignment with dynamic business goals.  

 

Question 2:
Write ten (10) user stories for a book-borrowing website for a library. Write it in the format: `As a ____, I want to ____, so that _____`.

### User Stories for a Book-Borrowing Website  

1. **As a** library member, **I want to** search for books by title, author, or genre, **so that** I can quickly find books I’m interested in borrowing.  
2. **As a** guest user, **I want to** browse available books without logging in, **so that** I can decide if I want to register as a member.  
3. **As a** member, **I want to** reserve a book online, **so that** I can pick it up later when it’s available.  
4. **As a** librarian, **I want to** mark books as "checked out" or "returned" in the system, **so that** the catalog stays up-to-date.  
5. **As a** member, **I want to** view my borrowing history, **so that** I can keep track of books I’ve read or plan to re-borrow.  
6. **As a** librarian, **I want to** receive automatic alerts for overdue books, **so that** I can follow up with members promptly.  
7. **As a** member, **I want to** renew a borrowed book online, **so that** I can extend my borrowing period without visiting the library.  
8. **As an** administrator, **I want to** manage user accounts (e.g., activate, deactivate, or reset passwords), **so that** the system remains secure and user-friendly.  
9. **As a** member, **I want to** set up email/SMS notifications for due dates, **so that** I avoid late return fines.  
10. **As a** librarian, **I want to** add new books to the catalog with cover images and descriptions, **so that** members can discover recent additions easily.  

 
Question 3: 
Define [Acceptance Criteria](https://resources.scrumalliance.org/Article/need-know-acceptance-criteria) for 3 to 5 user stories out of the 10 user stories you have defined.

 Answer:

### Acceptance Criteria for Selected User Stories  

**1. User Story #3**  
*As a member, I want to reserve a book online, so that I can pick it up later when it’s available.*  
- **Acceptance Criteria:**  
  - The system must display a "Reserve" button only if the book is currently checked out by another member.  
  - Upon reservation, the book’s status changes to "On Hold" in the catalog.  
  - The member receives an email/SMS notification when the reserved book becomes available.  
  - Reservations expire automatically after 48 hours if the member does not pick up the book.  
  - A member cannot reserve more than 5 books simultaneously.  

---

**2. User Story #4**  
*As a librarian, I want to mark books as "checked out" or "returned" in the system, so that the catalog stays up-to-date.*  
- **Acceptance Criteria:**  
  - The librarian must scan or manually enter the book’s ISBN and member’s ID to check out a book.  
  - Upon checkout, the system updates the book’s status to "Checked Out" and assigns a due date (e.g., 14 days later).  
  - When a book is marked as "Returned," the system updates its status to "Available" and removes it from the member’s active borrow list.  
  - Overdue fines (if applicable) are calculated automatically upon return and added to the member’s account.  

---

**3. User Story #7**  
*As a member, I want to renew a borrowed book online, so that I can extend my borrowing period without visiting the library.*  
- **Acceptance Criteria:**  
  - The "Renew" option is only visible if the book has no active holds from other members.  
  - Renewal extends the due date by the original borrowing period (e.g., 14 days).  
  - A member can renew a book up to 2 times.  
  - The system sends a confirmation email/SMS with the new due date after renewal.  

---

**4. User Story #9**  
*As a member, I want to set up email/SMS notifications for due dates, so that I avoid late return fines.*  
- **Acceptance Criteria:**  
  - Members can enable/disable notifications via their account settings.  
  - The system sends a reminder 3 days before the due date and on the due date itself.  
  - Notifications include the book title, due date, and a link to renew (if eligible).  
  - If a member has invalid contact details, the system logs an error for administrators.  

---

**5. User Story #1**  
*As a library member, I want to search for books by title, author, or genre, so that I can quickly find books I’m interested in borrowing.*  
- **Acceptance Criteria:**  
  - The search bar accepts partial keywords (e.g., "Har" returns "Harry Potter").  
  - Results are sorted by relevance and availability (available books appear first).  
  - Filters allow narrowing results by publication year, format (e.g., eBook, physical), or language.  
  - A "No results found" message displays if no matches exist.  
 


### Submission 

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL. 


### References

_Example of Referencing Classmate_

Referenced the code block below from Terence.
```js
    function printMe(){
        console.log("I am a reference example");
    }
```

_Example of Referencing Online Resources_

- https://developer.mozilla.org/en-US/
- https://www.w3schools.com/html/
- https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github
- https://www.deepseek.com/
- https://chatgpt.com/

