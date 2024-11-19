# Design the Use Case Diagram of the Features and Functionalities`

This document outlines the creation and purpose of the **Use Case Diagram** for the Airbnb Clone backend. The diagram visualizes system interactions for core functionalities, highlighting the roles of users and their interactions with the system.

---

## Objective

To create a **Use Case Diagram** that visually represents the interactions between users and the backend system for key functionalities, such as:
- User registration and login
- Property management
- Property booking
- Payments

---

## Use Case Diagram Description

The Use Case Diagram is designed to capture all key actors and interactions, ensuring a clear understanding of the system’s features.

### **Key Components:**
1. **Actors**:
   - **Guest**: Can register, search for properties, book properties, and make payments.
   - **Host**: Can register, list properties, manage property availability, and view bookings.
   - **Admin**: Manages user accounts and monitors system activity.

2. **Use Cases**:
   - **User Registration and Login**:
     - Guests and Hosts can register and log in to the platform securely.
   - **Property Management**:
     - Hosts can add, update, or remove property listings.
   - **Property Booking**:
     - Guests can search for and book available properties.
   - **Payments**:
     - Guests can securely process payments for bookings.
     - Hosts receive payouts for bookings.

3. **Relationships**:
   - Arrows show interactions between actors and use cases.
   - Includes associations like "extends" or "includes" for related functionalities.

---

## Diagram Visualization

A visual representation of the **Use Case Diagram** has been created using **Draw.io**. The file is stored in the directory `use-case-diagram/` in the repository.

### Preview:
![Use Case Diagram](use-case-diagram/use-case-diagram.png)

---

## Instructions for Developers

1. **Diagram Creation**:
   - Open [Draw.io](https://app.diagrams.net/) and design the Use Case Diagram based on the backend features.
   - Ensure all key actors, use cases, and relationships are clearly represented.

2. **Directory Structure**:
   - Save the diagram as `use-case-diagram.png`.
   - Store the file in the `use-case-diagram/` directory.

3. **Commit and Push**:
   - Add the file to the repository:
     ```bash
     git add use-case-diagram/use-case-diagram.png
     ```
   - Commit the changes:
     ```bash
     git commit -m "Added use case diagram for backend features"
     ```
   - Push the changes:
     ```bash
     git push origin main
     ```

---

## Repository Details

- **GitHub Repository:** [alx-airbnb-project-documentation](https://github.com/mosekyle/alx-airbnb-project-documentation)
- **Directory:** `use-case-diagram/`
- **File:** `use-case-diagram.png`

---

## Author

👤 **Moses Gitau**

- GitHub: [Moses Gitau](https://github.com/mosekyle)  
- LinkedIn: [Moses Gitau](https://www.linkedin.com/in/moses-gitau-kiarie)  

---

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](../LICENSE) file for more details.

