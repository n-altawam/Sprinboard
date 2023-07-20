The data is available as two attached CSV files:

_takehome_user_engagement. csv_
_takehome_users . csv_

The data has the following two tables:

**1.** A user table (_"takehome_users"_) with data on 12,000 users who signed up for the product in the last two years.  This table includes:
- **name:** the user's name
- **object_id:** the user's id
- **email:** email address
- **creation_source:** how their account was created. This takes on one of 5 values:
  - **PERSONAL_PROJECTS:** invited to join another user's personal workspace
  - **GUEST_INVITE:** invited to an organization as a guest (limited permissions)
  - **ORG_INVITE:** invited to an organization (as a full member)
  - **SIGNUP:** signed up via the website
  - **SIGNUP_GOOGLE_AUTH:** signed up using Google Authentication (using a Google email account for their login id)
- **creation_time:** when they created their account
- **last_session_creation_time:** unix timestamp of last login
- **opted_in_to_mailing_list:** whether they have opted into receiving marketing emails
- **enabled_for_marketing_drip:** whether they are on the regular marketing email drip
- **org_id:** the organization (group of users) they belong to
- **invited_by_user_id:** which user invited them to join (if applicable).

**2.** A usage summary table (_"takehome_user_engagement"_) that has a row for each day that a user logged into the product.

Defining an _"adopted user"_ as a user who _has logged into the product on three separate days in at least one seven­-day period_**, identify which factors predict future user adoption **.

We suggest spending 1­2 hours on this, but you're welcome to spend more or less. 
Please send us a brief writeup of your findings (the more concise, the better no more than one page), along with any summary tables, graphs, code, or queries that can help us understand your approach. Please note any factors you considered or investigation you did, even if they did not pan out. Feel free to identify any further research or data you think would be valuable.