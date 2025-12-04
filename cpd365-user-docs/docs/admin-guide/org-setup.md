
---

# **Organization Setup**

The **Organization Setup** area allows administrators to configure their healthcare facility, clinic, NDIS provider team, or training department within CPD365.
This is where you define your organization’s structure, branding, compliance settings, and default CPD expectations for staff.

This guide will walk you through adding your organization, configuring its details, and preparing the environment for your learners.

---

## **Who Can Access Organization Setup?**

Only the following user roles can view and manage organization settings:

* **Organization Admin**
* **Super Admin** (CPD365 internal role)

Learners and team managers do **not** have access to this section, ensuring sensitive settings remain secure.

---

## **Accessing the Organization Admin Dashboard**

To begin the setup:

1. Log in to CPD365
2. Click the **Admin** tab in the left navigation menu
3. Select **Organization Settings**

You’ll land on a multi-tab interface designed using **Progressive Disclosure** to keep complexity manageable.

---

## **Organization Profile**

The **Organization Profile** tab contains core identity fields.

You can update:

* Organization name
* Legal business name (optional)
* ABN/ACN (optional)
* Organization type

  * Hospital
  * Aged Care Facility
  * NDIS Provider
  * Community Health Service
  * Education / RTO
* Address
* Primary contact email (used for billing and admin notifications)
* Organization logo
  *(Displayed on certificates and internal dashboards)*

### Updating the Logo

Upload a PNG/JPG under 1.5MB.
The logo is automatically resized for certificates and reports.

!!! note
Learners will see the organization name and logo throughout the interface, helping support brand consistency.

---

## **Branding & Customization**

This tab allows your organization to tailor the learner experience.

### Options include:

* **Organization Colors** (used on dashboards, certificate borders)
* **Custom Welcome Message** shown on learner dashboard
* **Default Category Filters** (e.g., show only Aged Care + NDIS coursework)
* **Custom Footer Links** (e.g., internal policies)

These settings allow CPD365 to integrate smoothly with your internal training ecosystem.

---

## **CPD Requirements (Optional)**

Under the **CPD Requirements** tab, admins can define expectations for learners within their organization.

Settings include:

* Annual CPD target (e.g., 20 hours)
* CPD categories that require hours

  * Clinical Skills
  * Mandatory Training
  * Reflection & Professional Growth
* Minimum hours per category
* Automatic reminders for learners who fall behind

!!! tip
CPD requirements help ensure your workforce stays compliant and audit-ready, especially during accreditation cycles.

---

## **Default Course Visibility**

Choose how your learners see the course catalog.

### Options:

* **Full Library** — all CPD365 courses
* **Restricted Library** — only courses selected by admins
* **Hybrid** — featured courses + full catalog on request

This helps prevent information overload (Hick’s Law) and keeps staff focused on required competencies.

---

## **User Provisioning Settings**

This area controls how learners are added to the organization.

### Provisioning Options:

* **Manual Invitations** (individually add emails)
* **Bulk Import via CSV**

  * Accepts name, email, team, role
* **Self-Signup via Access Code**

  * Learners use a unique org code to join the organization
* **SSO Integrations** (if enabled)

  * Azure AD
  * Google Workspace

Each method follows **Error Prevention** principles (validation, sample CSVs, rollback on failed imports).

---

## **Team Structure**

If your organization has many staff, you can structure them into teams, such as:

* ICU
* ED
* Aged Care – Wing A
* NDIS High-Intensity Team
* Community Nursing Team

### Team Settings Include:

* Team name & description
* Assigned **Team Manager**
* Number of learners
* Default courses/programs for that team

This supports clearer reporting and easier competency management.

📘 *Optional screenshot placeholder:*
Team list showing team names, members count, and assigned manager.

---

## **Compliance Settings**

These settings help organization administrators meet regulatory or accreditation requirements.

You can enable:

* Mandatory courses with due dates
* Auto-reminders for overdue learning
* Certificate storage policies
* Organization-wide CPD export frequency
* Required fields for learner profiles (e.g., AHPRA number)

!!! warning
Once mandatory courses are assigned with a due date, learners cannot unenroll from them.

---

## **Audit & Reporting Defaults**

Admins can configure organization-level reporting preferences such as:

* Default reporting period (month, quarter, year)
* Preferred export format (CSV, PDF)
* Automatic delivery of compliance reports to certain emails
* Custom fields for reporting (e.g., site location, employment type)

This setup reduces repetitive actions and supports **Nielsen’s principle of efficiency for frequent users**.

---

## **Deleting or Deactivating an Organization**

Only CPD365 Super Admins can delete an organization.
However, Organization Admins may request:

* Organization deactivation
* Transfer of ownership
* Export of all organization data (courses, logs, users)

!!! warning
Organization deactivation removes learner access and cannot be undone without CPD365 support.

---

## **Next Steps**

After setting up your organization, continue configuring your environment:

➡️ **[Managing Learners & Teams →](user-management.md)**
Add learners, create teams, and assign roles.

➡️ **[Assigning Courses & Programs →](course-assignment.md)**
Start enrolling staff into required education.

➡️ **[Reports & Analytics →](reporting-analytics.md)**
Track CPD hours, progress, and compliance.