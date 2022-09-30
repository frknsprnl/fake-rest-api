# fake-rest-api

### **baseURL** : https://fakerestapifs.herokuapp.com/
<br>

<pre>
<b>GET | GET ALL EMPLOYEES</b>

<a href="https://fakerestapifs.herokuapp.com/employees">/employees</a> 
</pre>

<pre>
<b>GET | GET ALL ROLES</b>

<a href="https://fakerestapifs.herokuapp.com/roles">/roles</a> 
</pre>

<pre>
<b>GET | GET EMPLOYEE BY ID</b>

<a>/employees/<b>:employee_id</b></a> 
</pre>

<pre>
<b>GET | GET ROLES EMBED EMPLOYEES</b>

<a href="https://fakerestapifs.herokuapp.com/roles?_embed=employees">/roles<b>?_embed=employees</b></a> 
</pre>

<pre>
<b>GET | GET EMPLOYEES EXPAND ROLES</b>

<a href="https://fakerestapifs.herokuapp.com/employees?_expand=role">/employees<b>?_expand=role</b></a> 
</pre>

<pre>
<b>POST | CREATE NEW EMPLOYEE</b>

<a>/employees</a> 
</pre>

<pre>
<b>PUT/PATCH | UPDATE EMPLOYEE</b>

<a>/employees/<b>:employee_id</b></a> 
</pre>

<pre>
<b>DELETE | DELETE EMPLOYEE</b>

<a>/employees/<b>:employee_id</b></a> 
</pre>
