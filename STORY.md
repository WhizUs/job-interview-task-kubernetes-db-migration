# The Story

## WhizKube Consult

Alice, Bob, and you work together at WhizKube Consult. As a team, the three of you are responsible for supporting various customers with Kubernetes-related inquiries.

Your team leader, Kate, approaches you with a customer request and asks for your assistance.

The customer was running several applications on Kubernetes that used a database. Initially, migrations were only performed when a single application was launched. However, since another team also wanted to manipulate the data and schema of the database, migrations were performed when another application was launched as well.

Everything worked more or less stable until the customer started to scale the application horizontally. Suddenly, there were regular problems with the database migrations, and the migrations seemed to fail randomly for the client.

The customer also provided a current architecture overview:

![Architecture Diagram](./arch/architecture-diagram.png)

The client was frustrated and contacted Kate for help.

---

Alice, Bob, and you consult about what to do:

*Alice:* Hey! I think the best thing would be to look at different ways of doing the migrations and then present them to the clients. I think there is a way to do it through the CD pipeline, but probably there are better options as well.

*Bob:* It's probably worth looking into the current architecture as well.

*Alice:* That's what I thought too. Let's start working on it.
