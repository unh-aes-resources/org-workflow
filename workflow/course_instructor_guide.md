# Guide for Course Instructors

## Detailed Workflow:
Types of organizations in the University of New Hampshire enterprise:


### **1. Students coursework:**  
Course organization for students in the course in a given semester.
- Naming convention:
  year-term-comp-course_id
  For example, 2020-spring-comp-721-821, 2020-spring-comp-525


- Access rights:
  Course instructors and lab assistants will have owner access for the organization. Students will be members.

- The course instructor needs to provide the list of students to a tech consultant so as to add them to the organization. All the students will be added to this organization as members.


- Teams:
  - Students: All the students will be added to the “Students” team.
  - For teamwork or group projects, sub-teams are created under the “Students” team with naming convention team_number-aaa-bbb, where aaa and bbb are GitHub usernames of students in the sub-team.


- Repositories:

  This organization will have individual student repositories, starter code repositories, and the project team repositories.

  - __Individual Student repositories:__

    These repositories will contain all the individual submissions of the students like homework, labs, etc.
    - Naming convention:
      firstname-lastname (tbd)
      For homework and labs,
        Individual: hw_name/number-firstname
        Group: hw_name/number-xxx-yyy, where xxx, yyy are the first names of students in this group.

    - Access rights:

      All the students of the course will be added to the respective course organization as members by tech-consultant. Students should be given “write” access for their respective repositories.

      *Note* : “Students” team with all the students in it allows them to create their own empty repositories in the GitHub organizations.


    - Students can create their own repositories and make them available for the instructor and assistant to read.  If repositories are created by tech-consultants, they should be given “write” access.

  - __Starter code repositories:__

    - This repository contains the starter code and is maintained by the course instructor and assistant. Students will need to clone the starter code every week.  

    - Access rights: Students will have “read” access to this repository.

  - __Team project repositories:__

    - Sub-teams can be created under the “Students” team. This team will have maintainer access to a project repository where each team member can be a contributor.

-----------------
### **2. Course Materials:**
Course organization for course instructor and assistant.

- Naming convention: <course name>, for example, data-structures-fundamentals with blue logo.


- Access rights: Course instructor and assistant will be owners. Students **DO NOT** have access to this organization.


- Repositories in this organization:

  - __Course static website repository:__
    This is a GitHub pages website for the course.

    Naming convention: compxxx.github.io, xxx represents course ID.
    Note: There is a static website which is being maintained at present: [unh-aes-resources](https://unh-aes-resources.github.io/)

  - __Starter code repositories.__
    This repository contains the starter code used for labs.


  - __Lab and homework solution repositories.__
    Assistants will upload the solutions to homework and labs in this repository. These repositories are considered to be useful in future semesters.
---------------

### **3. Student Projects:** (To be Considered)
- Organization for Student projects that relate to a course.

- Teams:
  - Students: All the students in the course.
  - Project teams: Sub-teams of Students.


- Repositories:

  Project repository corresponding to project teams.

- Access rights:
  - Owners are course instructor and lab assistants.
  - Project team members are maintainers of their repository and readers of all other repositories.

------------

## At the end of each semester:
- "Student coursework" organizations get recycled **AFTER** grades are submitted.
  All student repositories are removed. Starter code and solutions repositories are moved to the Course Materials.

- “Course Materials” organizations persist over time.
  The organization is renamed to reflect the following semester or the entire organization is removed and a new one is created.

- "Student Projects" organizations get updated at the end of each semester.
