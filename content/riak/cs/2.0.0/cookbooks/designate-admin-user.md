---
title: "Designating an Admin User"
description: ""
project: "riak_cs"
project_version: "2.0.0"
aliases:
  - /riakcs/2.0.0/cookbooks/Designating-an-Admin-User/
  - /riak/cs/2.0.0/cookbooks/Designating-an-Admin-User/
---

Once a user has been created, you should designate a user as an admin by
editing and replacing the `admin_key` and `admin_secret` in `app.config`
with the user's credentials. Once this is done, do not forget to update
the same credentials in the Stanchion `app.config` as well.

<div class="note">
<div class="title">Note on the admin role</div>
This is a powerful role and gives the designee administrative
capabilities within the system. As such, caution should be used to
protect the access credentials of the admin user.
</div>
