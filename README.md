# Kubernetes Database Migration

In this task we will look in a common task every developer has to face: Database Migrations.


## Guidance

1. Create a Kubernetes Cluster on an environment you prefer (e.g. minikube, or use a managed kubernetes cluster on an cloud provider - Exoscale, AWS, Azure)
2. Read [the story](STORY.md)
3. Read the [notes](NOTES.md)
4. Review what Alice and Bob have brainstormed.


## Additional task

* Maybe also think about how the database is hosted at customerside. What may be advantages hosting a database in Kubernetes vs. running it outside of Kubernetes?Do you have any suggestions on how you would run the databases?

## Notes

* used techstack:
  * [Kubernetes](https://kubernetes.io/)
  * [Kubernetes Jobs](https://kubernetes.io/docs/concepts/workloads/controllers/job/)
  * [DB Migrations](https://martinfowler.com/articles/evodb.html)