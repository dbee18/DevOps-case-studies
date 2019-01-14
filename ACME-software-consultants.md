# ACME Software Consultants

ACME is a small company delivering software work billed by the hour its customers.
ACME primarily delivers a set of extensions to a third party platform. The platform is called Team Power, their plugin is called Foundation.

## The Team

ACME Software Consultants is a team of 8 developers, 4 salespersons and the two founders.
One of the founders is the CTO, the other CEO.
One of the salespersons, let's call her Michelle functions as the De Facto project manager. She has no formal responsibility, but stepped up, because someone had to.

## The Product

For Foundation work generally comes in three flavours. Bugs in production that will be fixed at no charge. Updating the plugin to work with new versions of Team Power also comes free of charge. New features comes from the salespersons engaging with new and existing customers. The feature will be estimated and broken down, in order to give a budget to the customer.

Internal Improvements are not prioritized as _"The customers do not want to pay for automated testing"_.

Building on top of Team Power comes with its own set of challenges. The Elbonian company developing Team Power does not have great documentation, and they are not very transparent about what happens from release to release. This often has the consequence that the ACME team must run very fast when suddenly some of their customer deployments break after an outage.

All the source code for Foundation lives in a single Git repository. The team is using [The Git Flow](https://nvie.com/posts/a-successful-git-branching-model/).

The team has three two-week sprints, and then a two week hardening period for approval tests. The team is supposed to only work on bug fixes and internal quality in the hardening period, but the CTO often sneaks in a pet feature in this period.

Deploying to customers is painful. The infrastructure they deploy to is completely in the hands of the customers. Different setups, access rights, firewalls and other constraints create highly variant systems from customer to customer.

As a consequence of being heavily tied to invoicable hours and building a product on a third party platform they have no unit tests and very little effort has been made in this area.

The team delivers value to their customers but it grows more difficult every release, having to apply workarounds and perform heroics to deliver on time.

## Cases

In this section we describe the different roles that could try to influence the way of working at ACME Software Consultants.
For each section discuss how to make problems and solutions visible. As well as a (short) prioritized list of things to do/investigate.

### Developer

You are a developer at ACME Software Consultants, frustrated with the ever decreasing quality of the software craftsmanship at ACME.

### Consultant

Whether you call it an _"Agile Coach"_, _"DevOps Consultant"_ or some other denomination, you have been called upon to provide your assistance to ACME.
Where and how to start this engagement should be a focus for this discussion.

### Project Manager

You are Michelle, the De Facto project manager. You try to balance the many needs of developers, customers and upper management. It feels like you do nothing but go to
non-productive meetings and spend your time in conflict resolution mode all the time.

### CTO

You are the CTO of ACME. It feels like it takes too long from business case to deployment at customers. As you look over the time sheets you have noticed more time is being spent
on support and maintenance work than new features. Your developers seem both slower and grumpier, and you don't know why.