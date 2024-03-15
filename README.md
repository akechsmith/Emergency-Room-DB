# Emergency-Room-DB

Our database schema for a hospital management system includes tables for shifts, doctors, receptionists, nurses, patients, beds, medications, and persons associated with various roles in the hospital.

*  PERSON: Stores information about individuals, including their last name, first name, and middle name.

*  ADDRESS: Contains addresses associated with individuals, including details such as country, province, city, street, and street number.

*  CONTACT: Stores contact information like email addresses and telephone numbers linked to individuals.

*  WORKER: Holds data about workers in the emergency room, including their worker ID, worker type, and associated person ID.

*  RECEPTIONIST: Tracks receptionists in the emergency room, linked to worker IDs.

*  NURSE: Stores information about nurses, linked to worker IDs.

*  DOCTOR: Contains data about doctors, linked to worker IDs.

*  SHIFT: Represents shifts in the emergency room, with a unique shift ID and start and end times.

*  Shift_Assignment: Associates workers with shifts, indicating whether they are triage doctors.

*  PATIENT: Stores data about patients, linked to person IDs.

*  ADMISSION: Tracks admissions of patients, linking patient IDs, receptionist IDs, and shift IDs.

*  BED: Contains information about beds, including bed IDs and the nurse responsible for each bed.

*  MEDICATION: Stores medications available in the emergency room, with unique medication IDs and names.

*  PRESCRIPTION: Tracks prescriptions issued to patients, including patient IDs, medication IDs, dosage, and frequency per day.

*  Medication_Administration: Records the administration of medications, linking prescription IDs and nurse IDs.

Our scripts includes foreign key constraints to maintain data integrity and ensure referential integrity between related tables.

Overall, this schema provides a foundation for managing hospital operations, including patient care, staff scheduling, and medication management at the Emergency Room.

### CONTRIBUTORS
[Akech Atem](https://github.com/akechsmith), [Derrick Gacheru](https://github.com/gacheruh)
