+++
aliases = ["/post/149270751043/one-of-my-favorite-bugs-in-this-class-from-an"]
date = 2016-08-21T14:20:52Z
id = "149270751043"
slug = "one-of-my-favorite-bugs-in-this-class-from-an"
type = "tumblr-quote"

[tumblr]
can_blaze = false
post_url = "https://indirect.tumblr.com/post/149270751043/one-of-my-favorite-bugs-in-this-class-from-an"
id = 149270751043.0
is_blazed = false
reblog_key = "8HXgnmTK"
source = "<a href=\"http://danluu.com/concurrency-bugs/##One+of+my+favorite+bugs+in+this+class+from+an+actual+system+was+in+a+ring-based+storage+system+where+nodes+could+do+health+checks+on+their+neighbors+and+declare+that+their+neighbors+should+be+dropped+if+the+health+check+fails.+One+node+went+bad%2C+dropped+all+of+its+storage%2C+and+started+reporting+its+neighbors+as+bad+nodes.+Its+neighbors+noticed+that+the+bad+node+was+bad%2C+but+because+the+bad+node+had+dropped+all+of+its+storage%2C+it+was+super+fast+and+was+able+to+report+its+good+neighbors+before+the+good+neighbors+could+report+the+bad+node.+After+ejecting+its+immediate+neighbors%2C+to+bad+node+got+new+neighbors+and+raced+the+new+neighbors%2C+winning+again+for+the+same+reason.+This+was+repeated+until+the+entire+cluster+died.\">Notes on concurrency bugs</a>"
is_blaze_pending = false
state = "published"
text = "One of my favorite bugs in this class from an actual system was in a ring-based storage system where nodes could do health checks on their neighbors and declare that their neighbors should be dropped if the health check fails. One node went bad, dropped all of its storage, and started reporting its neighbors as bad nodes. Its neighbors noticed that the bad node was bad, but because the bad node had dropped all of its storage, it was super fast and was able to report its good neighbors before the good neighbors could report the bad node. After ejecting its immediate neighbors, to bad node got new neighbors and raced the new neighbors, winning again for the same reason. This was repeated until the entire cluster died."
can_send_in_message = true
blog_name = "indirect"
should_open_in_legacy = true
can_reblog = false
display_avatar = true
type = "quote"
slug = "one-of-my-favorite-bugs-in-this-class-from-an"
date = "2016-08-21 14:20:52 GMT"
timestamp = 1471789252.0
format = "markdown"
summary = "One of my favorite bugs in this class from an actual system was in a ring-based storage system where nodes could do health..."
can_reply = false
is_blocks_post_format = false
id_string = "149270751043"
note_count = 0.0
interactability_blaze = "everyone"
short_url = "https://tmblr.co/ZY3jby2B1EkT3"
can_like = false
interactability_reblog = "everyone"

[tumblr.blog]
title = "indirect"
description = ""
url = "https://indirect.tumblr.com/"
uuid = "t:PgyUJU3SA2Klwyt81UWAwQ"
updated = 1739757070.0
can_show_badges = true
name = "indirect"

[tumblr.blog.tumblrmart_accessories]

[tumblr.reblog]
comment = "<p><a href=\"http://danluu.com/concurrency-bugs/##One+of+my+favorite+bugs+in+this+class+from+an+actual+system+was+in+a+ring-based+storage+system+where+nodes+could+do+health+checks+on+their+neighbors+and+declare+that+their+neighbors+should+be+dropped+if+the+health+check+fails.+One+node+went+bad%2C+dropped+all+of+its+storage%2C+and+started+reporting+its+neighbors+as+bad+nodes.+Its+neighbors+noticed+that+the+bad+node+was+bad%2C+but+because+the+bad+node+had+dropped+all+of+its+storage%2C+it+was+super+fast+and+was+able+to+report+its+good+neighbors+before+the+good+neighbors+could+report+the+bad+node.+After+ejecting+its+immediate+neighbors%2C+to+bad+node+got+new+neighbors+and+raced+the+new+neighbors%2C+winning+again+for+the+same+reason.+This+was+repeated+until+the+entire+cluster+died.\">Notes on concurrency bugs</a></p>"
tree_html = ""
+++
