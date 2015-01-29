
User generated session ids should be rejected by the server  

-------


**Description:**

Whenever user generated session ids are not rejected by the server, an attacker could change the session credentials given by the server on the targets computer into an easy to remember value.

When the attacker then changes his own session credentials with the easily to remember value he used on the target's computer. The attacker could do a session hijacking on the targets current session.




**Solution:**

All session ids not generated by the server should be rejected.	