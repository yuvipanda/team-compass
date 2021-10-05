# Cloud project access

We manage many projects across multiple cloud providers. This
document defines our access policy, and is the canonical location
for the projects we *do* have access to.

## Access policy

Every 2i2c engineer should have equal access to every cloud project
we maintain. This prevents particular individuals from becoming
single points of failure.

In some cases, this requires paperwork for each engineer to get
access. We should try to find ways around this, but if not,
just do the paperwork.

## Google Cloud Access

On Google Cloud, we have a [2i2c organization](https://console.cloud.google.com/projectselector2/home/dashboard?organizationId=184174754493&supportedpurview=project),
that contains some projects we are fully responsible for. Access
to *all* projects in this organization can be granted by
adding the user to the group `gcp-organization-admins@2i2c.org`
in the [Google Workspace Admin dashboard](https://admin.google.com/ac/users)
(available only to admins of the 2i2c.org Google Workspace account).
Note that this option is only available for engineers with a `@2i2c.org`
account.

For all other projects, we will need to make a manual entry in
the project's [IAM Page](https://console.cloud.google.com/iam-admin/iam)
for the engineer's `@2i2c.org` account, with `Owner` permissions.

The canonical list of GCP projects we have access to is maintained
[in this google sheet](https://docs.google.com/spreadsheets/d/1NSaAKLG2_njXxs6JlGUAhSWeHONz9QSGLVwEK790IZo/edit#gid=846555027)

## AWS Access

Each 2i2c engineer should get an individual [IAM User Account](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users.html)
in every AWS account we have access to. This should have the broadest
set of permissions as well, and the same set of permissions for everyone.

The canonical list of AWS accounts we have access to is maintained
[in this google sheet](https://docs.google.com/spreadsheets/d/1NSaAKLG2_njXxs6JlGUAhSWeHONz9QSGLVwEK790IZo/edit#gid=537065664)