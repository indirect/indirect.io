+++
aliases = ["/post/149270751043/one-of-my-favorite-bugs-in-this-class-from-an"]
date = 2016-08-21T14:20:52Z
id = "149270751043"
slug = "one-of-my-favorite-bugs-in-this-class-from-an"
type = "tumblr-quote"

[tumblr]
interactability_reblog = "everyone"
can_send_in_message = true
can_reply = false
display_avatar = true
post_url = "https://indirect.io/post/149270751043/one-of-my-favorite-bugs-in-this-class-from-an"
format = "markdown"
id_string = "149270751043"
date = "2016-08-21 14:20:52 GMT"
text = "One of my favorite bugs in this class from an actual system was in a ring-based storage system where nodes could do health checks on their neighbors and declare that their neighbors should be dropped if the health check fails. One node went bad, dropped all of its storage, and started reporting its neighbors as bad nodes. Its neighbors noticed that the bad node was bad, but because the bad node had dropped all of its storage, it was super fast and was able to report its good neighbors before the good neighbors could report the bad node. After ejecting its immediate neighbors, to bad node got new neighbors and raced the new neighbors, winning again for the same reason. This was repeated until the entire cluster died."
is_blazed = false
is_blaze_pending = false
source = "<a href=\"http://danluu.com/concurrency-bugs/##One+of+my+favorite+bugs+in+this+class+from+an+actual+system+was+in+a+ring-based+storage+system+where+nodes+could+do+health+checks+on+their+neighbors+and+declare+that+their+neighbors+should+be+dropped+if+the+health+check+fails.+One+node+went+bad%2C+dropped+all+of+its+storage%2C+and+started+reporting+its+neighbors+as+bad+nodes.+Its+neighbors+noticed+that+the+bad+node+was+bad%2C+but+because+the+bad+node+had+dropped+all+of+its+storage%2C+it+was+super+fast+and+was+able+to+report+its+good+neighbors+before+the+good+neighbors+could+report+the+bad+node.+After+ejecting+its+immediate+neighbors%2C+to+bad+node+got+new+neighbors+and+raced+the+new+neighbors%2C+winning+again+for+the+same+reason.+This+was+repeated+until+the+entire+cluster+died.\">Notes on concurrency bugs</a>"
interactability_blaze = "everyone"
type = "quote"
summary = "One of my favorite bugs in this class from an actual system was in a ring-based storage system where nodes could do health..."
should_open_in_legacy = true
is_blocks_post_format = false
id = 149270751043.0
short_url = "https://tmblr.co/ZY3jby2B1EkT3"
note_count = 0.0
can_blaze = false
timestamp = 1471789252.0
reblog_key = "8HXgnmTK"
can_reblog = false
blog_name = "indirect"
slug = "one-of-my-favorite-bugs-in-this-class-from-an"
state = "published"
can_like = false

[tumblr.blog]
description = ""
url = "https://indirect.io/"
uuid = "t:PgyUJU3SA2Klwyt81UWAwQ"
updated = 1739939727.0
can_show_badges = false
name = "indirect"
title = "indirect"

[tumblr.blog.tumblrmart_accessories]

[tumblr.reblog]
comment = "<p><a href=\"http://danluu.com/concurrency-bugs/##One+of+my+favorite+bugs+in+this+class+from+an+actual+system+was+in+a+ring-based+storage+system+where+nodes+could+do+health+checks+on+their+neighbors+and+declare+that+their+neighbors+should+be+dropped+if+the+health+check+fails.+One+node+went+bad%2C+dropped+all+of+its+storage%2C+and+started+reporting+its+neighbors+as+bad+nodes.+Its+neighbors+noticed+that+the+bad+node+was+bad%2C+but+because+the+bad+node+had+dropped+all+of+its+storage%2C+it+was+super+fast+and+was+able+to+report+its+good+neighbors+before+the+good+neighbors+could+report+the+bad+node.+After+ejecting+its+immediate+neighbors%2C+to+bad+node+got+new+neighbors+and+raced+the+new+neighbors%2C+winning+again+for+the+same+reason.+This+was+repeated+until+the+entire+cluster+died.\">Notes on concurrency bugs</a></p>"
tree_html = ""
+++
