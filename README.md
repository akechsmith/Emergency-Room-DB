# Emergency-Room-DB

Our database schema for a hospital management system includes tables for shifts, doctors, receptionists, nurses, patients, beds, medications, and persons associated with various roles in the hospital.

*  SHIFT: Stores information about different shifts in the hospital, such as start time and end time.

*  DOCTOR: Contains details about doctors working in the hospital, including their assigned shift.

*  RECEPTIONIST: Stores data about receptionists, including their assigned shift.

*  NURSE: Holds information about nurses, including their assigned shift.

*  PATIENT: Stores information about patients admitted to the hospital, including admission time, assigned doctor, receptionist, and bed.

*  BED: Contains information about beds in the hospital, including the nurse and patient assigned to each bed.

*  MEDICATION: Stores details about medications prescribed to patients, including dosage and administration frequency. It also tracks the doctor and nurse responsible for the medication.

*  PERSON: General information about persons associated with the hospital, including patients, receptionists, doctors, and nurses.

Our scripts includes foreign key constraints to maintain data integrity and ensure referential integrity between related tables.

Overall, this schema provides a foundation for managing hospital operations, including patient care, staff scheduling, and medication management.

### CONTRIBUTORS
[Akech Atem](https://github.com/akechsmith)
