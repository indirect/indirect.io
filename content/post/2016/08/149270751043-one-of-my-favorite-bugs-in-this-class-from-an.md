+++
aliases = ["/post/149270751043/one-of-my-favorite-bugs-in-this-class-from-an"]
date = 2016-08-21T14:20:52Z
id = "149270751043"
slug = "one-of-my-favorite-bugs-in-this-class-from-an"
type = "tumblr-quote"

[tumblr]
id = 149270751043.0
text = "One of my favorite bugs in this class from an actual system was in a ring-based storage system where nodes could do health checks on their neighbors and declare that their neighbors should be dropped if the health check fails. One node went bad, dropped all of its storage, and started reporting its neighbors as bad nodes. Its neighbors noticed that the bad node was bad, but because the bad node had dropped all of its storage, it was super fast and was able to report its good neighbors before the good neighbors could report the bad node. After ejecting its immediate neighbors, to bad node got new neighbors and raced the new neighbors, winning again for the same reason. This was repeated until the entire cluster died."
can_reply = false
display_avatar = true
id_string = "149270751043"
is_blazed = false
format = "markdown"
type = "quote"
can_blaze = false
post_url = "https://indirect.io/post/149270751043/one-of-my-favorite-bugs-in-this-class-from-an"
can_like = false
can_send_in_message = true
blog_name = "indirect"
is_blaze_pending = false
timestamp = 1471789252.0
interactability_reblog = "everyone"
interactability_blaze = "everyone"
is_blocks_post_format = false
date = "2016-08-21 14:20:52 GMT"
note_count = 0.0
summary = "One of my favorite bugs in this class from an actual system was in a ring-based storage system where nodes could do health..."
can_reblog = false
state = "published"
reblog_key = "8HXgnmTK"
short_url = "https://tmblr.co/ZY3jby2B1EkT3"
should_open_in_legacy = true
slug = "one-of-my-favorite-bugs-in-this-class-from-an"
source = "<a href=\"http://danluu.com/concurrency-bugs/##One+of+my+favorite+bugs+in+this+class+from+an+actual+system+was+in+a+ring-based+storage+system+where+nodes+could+do+health+checks+on+their+neighbors+and+declare+that+their+neighbors+should+be+dropped+if+the+health+check+fails.+One+node+went+bad%2C+dropped+all+of+its+storage%2C+and+started+reporting+its+neighbors+as+bad+nodes.+Its+neighbors+noticed+that+the+bad+node+was+bad%2C+but+because+the+bad+node+had+dropped+all+of+its+storage%2C+it+was+super+fast+and+was+able+to+report+its+good+neighbors+before+the+good+neighbors+could+report+the+bad+node.+After+ejecting+its+immediate+neighbors%2C+to+bad+node+got+new+neighbors+and+raced+the+new+neighbors%2C+winning+again+for+the+same+reason.+This+was+repeated+until+the+entire+cluster+died.\">Notes on concurrency bugs</a>"

[tumblr.blog]
name = "indirect"
title = "indirect"
description = ""
url = "https://indirect.io/"
uuid = "t:PgyUJU3SA2Klwyt81UWAwQ"
updated = 1739927643.0
can_show_badges = false

[tumblr.blog.tumblrmart_accessories]

[tumblr.reblog]
comment = "<p><a href=\"http://danluu.com/concurrency-bugs/##One+of+my+favorite+bugs+in+this+class+from+an+actual+system+was+in+a+ring-based+storage+system+where+nodes+could+do+health+checks+on+their+neighbors+and+declare+that+their+neighbors+should+be+dropped+if+the+health+check+fails.+One+node+went+bad%2C+dropped+all+of+its+storage%2C+and+started+reporting+its+neighbors+as+bad+nodes.+Its+neighbors+noticed+that+the+bad+node+was+bad%2C+but+because+the+bad+node+had+dropped+all+of+its+storage%2C+it+was+super+fast+and+was+able+to+report+its+good+neighbors+before+the+good+neighbors+could+report+the+bad+node.+After+ejecting+its+immediate+neighbors%2C+to+bad+node+got+new+neighbors+and+raced+the+new+neighbors%2C+winning+again+for+the+same+reason.+This+was+repeated+until+the+entire+cluster+died.\">Notes on concurrency bugs</a></p>"
tree_html = ""
+++
