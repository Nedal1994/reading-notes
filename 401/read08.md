# Read08 Summary

![rbac](https://www.dnsstuff.com/wp-content/uploads/2019/10/role-based-access-control.jpg)

RBAC is role-based, so depending on your role in the organization, you will have different access permissions. This is determined by an administrator, who sets the parameters of what access a role should have, along with which users are assigned which roles. For instance, some users may be assigned to a role where they can write and edit particular files, whereas other users may be in a role restricted to reading files but not editing them. It’s possible for one user to be assigned multiple roles, giving them access to numerous different files or abilities. Say there’s a team of people working on a large project. The project manager will have access to all the files and can edit and change things within the project. However, the development team might only be allowed access to the programming files and won’t be able to see or edit the financial information or employee details for the project. On the flip side, the human resources or management team might have access to all the employee and financial information but has no use for the programming files. An organization might use RBAC for projects like this because with RBAC, the policies don’t need to be changed every time a person leaves the organization or changes jobs: they can simply be removed from the role group or allocated to a new role. This also means new employees can be granted access relatively quickly, depending on the organizational role they fulfill.

**RBAC Implementation steps**

1. Inventory your systems

Figure out what resources you have for which you need to control access, if you don't already have them listed. Examples would include an email system, customer database, contact management system, major folders on a file server, etc. 

2. Analyze your workforce and create roles

You need to group your workforce members into roles with common access needs.  Avoid the temptation to have too many roles defined. Keep them as simple and stratified as possible.

For example, you might have a basic user role, which includes the access any employee would need, such as email and the intranet site. Another role might be a customer service rep, that would have read/write access to the customer database, and a customer database administrator, that would have full control of the customer database. 

3. Assign people to roles

Now that you have a list of roles and their access rights, figure out which role(s) each employee belongs in, and set their access accordingly. 

4. Never make one-off changes

Resist any temptation to make a one-off change for an employee with unusual needs. If you begin doing this, your RBAC system will quickly begin to unravel. Change the roles as required or add new ones when really necessary. 

5. Audit

Periodically review your roles, the employees assigned to them, and the access permitted for each. If you discover, for example, that a role has unnecessary access to a particular system, change the role and adjust the access level for all employees in that role. 

As an example, many healthcare organizations, given the need for regulatory compliance in controlling access to medical records, use RBAC to define exactly what access to medical records each type of clinician may need.  While a doctor might have almost unlimited access to the records of patients he/she manages, a receptionist might be limited to basic contact information needed to manage appointments.  Given the large number of staff members in well stratified roles, RBAC is an efficient way to control record access in compliance with HIPAA, and other regulations.