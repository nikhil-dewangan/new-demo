# new-demo
This is demo for Git &amp; Github Class.
git branch branch-name
JSON: JSON stands for JavaScript Object Notation. It's a lightweight data format that's easy for humans to read and write and easy for machines to parse and generate.
Advantages of Using JWT:
1. Stateless: The server doesn't need to keep a session store as the JWT itself contains the user state.
2. Scalable: Easier to scale across servers because no session information is stored on the server.
3. Compact: Because they are JSON-based, JWTs are compact and can be sent via URL, POST parameter, or inside an HTTP header.
4. Self-contained: The token contains all the information needed for authentication, including user permissions and expiry information.
Ping is a fundamental network administration command used to test and verify connectivity between devices on an Internet Protocol (IP) network.
It’s like saying, “Hey, are you there?” and waiting for a response.
The name “ping” comes from sonar technology, where pulses of sound are sent out and then echoed back.
app.delete('/users/:id', (req, res) => {
  const user = users.find(u => u.id === parseInt(req.params.id));
  if (!user) return res.status(404).send('User not found');
  const index = users.indexOf(user);
  users.splice(index, 1);
  res.json(user);
});

