
---

# **Managing Learners & Teams**

The **User Management** area allows Organization Admins to add learners, organize them into teams, assign roles, and maintain an accurate staff directory.

A clear, well-structured user list helps ensure your workforce completes required CPD on time and stays compliant with organizational and regulatory requirements.

---

## **Accessing User Management**

1. Log in as an Organization Admin
2. Open the **Admin** sidebar
3. Click **Learners & Teams**

You’ll land on a dashboard showing:

* Total learners
* Number of active/inactive users
* Number of teams
* Quick actions (Add Learners, Bulk Import, Add Team)

📸 *Placeholder screenshot:*
Learners table with columns: Name, Email, Team, Role, Status.

---

## **Adding Learners**

Admins can add learners in three ways, supporting different organizational needs.

---

### **1. Individual Invite (Recommended for small teams)**

1. Click **Add Learner**
2. Enter:

   * Name
   * Email
   * Role (Learner / Team Manager / Admin)
   * Team (optional)
3. Click **Send Invite**

The learner receives an email asking them to create their password and join the organization.

**Validation:**

* Tagged fields highlight errors instantly (Error Prevention)
* Email format is checked automatically

---

### **2. Bulk Import via CSV (Ideal for 10+ learners)**

Use bulk import when onboarding entire departments.

1. Click **Bulk Import**
2. Download the sample CSV
3. Fill in the required columns:

   * First Name
   * Last Name
   * Email
   * Role
   * Team (optional)
4. Upload the completed file
5. Review import summary
6. Click **Confirm Import**

### Import Reliability Features

* Duplicate email detection
* Row-by-row error reporting
* Undo option if an import needs reverting
* Safe rollback to prevent partial uploads

!!! tip
Keep team names consistent — mismatched spelling creates duplicate teams.

---

### **3. Self-Signup via Organization Code**

If enabled, your organization receives a unique **Access Code**.

Steps for learners:

1. Visit the CPD365 sign-up page
2. Enter their details
3. Enter the **organization access code**
4. They are automatically added to your org and assigned default settings

This option is commonly used by multi-site facilities and rotating clinical staff.

---

## **User Roles & Permissions**

CPD365 uses a clear, role-based permissions system:

| Role                   | Description           | Permissions                                               |
| ---------------------- | --------------------- | --------------------------------------------------------- |
| **Learner**            | Standard staff member | Take courses, view CPD, download certificates             |
| **Team Manager**       | Supervises a team     | View team progress, assign team courses, run team reports |
| **Organization Admin** | Primary admin         | Manage all learners, teams, settings, reporting           |
| **Billing Admin**      | Finance contact       | View/modify subscription, invoices, payments              |

### Role Visibility

Only Admins can see and edit user roles — promoting clarity and security.

---

## **Editing a Learner**

From the learner list:

1. Click the learner’s name
2. Edit fields such as:

   * Name
   * Profession
   * Email
   * Team
   * Role
   * Status
3. Click **Save Changes**

Changes apply instantly and learners are notified when necessary.

---

## **Deactivating a Learner**

When staff leave your organization, you can deactivate their accounts.

Deactivation effects:

* User loses login access
* Courses and CPD history remain stored for audit
* License seat becomes available (for subscription-based orgs)

### How to Deactivate

1. Open a learner’s profile
2. Click **Deactivate User**
3. Confirm the action

!!! warning
Deactivation cannot be undone without re-inviting the user.

---

## **Teams Overview**

Teams help structure learners, assign required training, and create targeted reports.

Typical team examples:

* Emergency Department
* ICU
* Aged Care – Night Shift
* NDIS High Intensity Team
* Community Care – Region B

Teams make large organizations easier to manage by adding hierarchy and grouping.

---

## **Creating a Team**

1. Go to **Learners & Teams → Teams**
2. Click **Add Team**
3. Enter:

   * Team name
   * Description (optional)
   * Assign a Team Manager
4. Click **Create Team**

Fewer than 5 required fields keeps this process fast (Hick’s Law).

---

## **Adding Learners to a Team**

There are three ways:

### From the Team Page

1. Select a team
2. Click **Add Members**
3. Choose learners from list

### From the Learner Profile

1. Open a learner
2. Select **Team** from dropdown
3. Save

### During Bulk Import

* Add the “Team” column in CSV

---

## **Managing Team Managers**

Team Managers can:

* View team progress
* Run team-level reports
* Assign optional courses
* Send reminders

Admins can assign or change a Team Manager anytime.

---

## **Filtering & Searching Learners**

The Learners table includes:

* Search bar
* Filters for:

  * Role
  * Team
  * Status (Active / Inactive)
  * Completion %
  * Profession

These tools are optimized to minimize cognitive load and enhance scanability.

!!! tip
Use filters when preparing audits or sending reminders before CPD deadlines.

---

## **Bulk Actions**

To save time, Admins can select multiple learners and apply actions:

* Assign program
* Move to team
* Send reminder email
* Deactivate
* Export selected learners

Bulk actions follow **Nielsen’s Efficiency Heuristics**, speeding up frequent admin tasks.

---

## **Audit Logs (Optional)**

For organizations with compliance requirements, CPD365 tracks:

* User role changes
* Team changes
* Deactivation events
* Course assignment changes

Logs can be exported as part of an accreditation cycle.

---

## **Troubleshooting User Management**

### Learner not receiving invite?

* Check spam folder
* Verify email spelling
* Resend the invitation from their profile

### Imported CSV not working?

* Check for special characters or extra spaces
* Ensure correct column order
* Confirm team names match existing teams (case sensitive)

### Learner in the wrong team?

* Edit their profile and update the Team field
* Ensure no conflicting CSV imports were made recently

---

## **Next Steps**

Your users and teams are now set up. Continue configuring your organization:

➡️ **[Assigning Courses & Programs →](course-assignment.md)**
Learn how to assign individual courses or full competency programs.

➡️ **[Reporting & Analytics →](reporting-analytics.md)**
Track team and organization-wide CPD activity.