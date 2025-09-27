This project demonstrates various SQL JOIN types to combine data across related tables:

INNER JOIN: Retrieves users who have at least one assigned role.

LEFT JOIN: Lists all users along with their profile information if available.

RIGHT JOIN: Shows all roles, even those not assigned to any user.

FULL OUTER JOIN (emulated): Combines all users and profiles, showing matches and unmatched entries.

CROSS JOIN: Produces every possible combination of users and roles.

SELF JOIN: Displays referral relationships between users.

Subquery with LEFT JOIN: Retrieves the latest login activity per user.



The /api/reports endpoints provide protected access to these data views for reporting:

/users-with-roles — Users and their roles.

/users-with-profiles — Users and their profile details.

/roles-right-join — All roles including unassigned ones.

/profiles-full-outer — Combined users and profiles data.

/user-role-combos — Every user-role pair possible.

/referrals — Referral relationships among users.

/latest-login — Most recent login per user.
