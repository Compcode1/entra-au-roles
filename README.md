Microsoft Entra built-in roles behave differently depending on their function—password resets, user lifecycle management, or policy control—and AU scope strictly governs their reach.

A user assigned to multiple AUs is visible and partially manageable by admins scoped to any of those units, but only within the role’s allowed actions and the AU’s boundary.

Password Administrator is a minimal risk role for frontline support; User Administrator enables deeper account and group changes; Authentication Policy Administrator governs how users authenticate—but requires scoped visibility to take effect.

This project mirrors real-world delegation needs in large organizations, where departments require autonomy without compromising security or overprovisioning.

Understanding the interaction between role type and AU scope is foundational to mastering Microsoft Entra identity management and performing well on SC-300.
