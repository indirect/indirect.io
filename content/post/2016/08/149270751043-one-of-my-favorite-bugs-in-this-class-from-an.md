+++
date = 2016-08-21T14:20:52Z
slug = "one-of-my-favorite-bugs-in-this-class-from-an"
id = "149270751043"
aliases = [ "/post/149270751043/one-of-my-favorite-bugs-in-this-class-from-an" ]
tags = [ ]
type = "tumblr-quote"

[tumblr]
text = "One of my favorite bugs in this class from an actual system was in a ring-based storage system where nodes could do health checks on their neighbors and declare that their neighbors should be dropped if the health check fails. One node went bad, dropped all of its storage, and started reporting its neighbors as bad nodes. Its neighbors noticed that the bad node was bad, but because the bad node had dropped all of its storage, it was super fast and was able to report its good neighbors before the good neighbors could report the bad node. After ejecting its immediate neighbors, to bad node got new neighbors and raced the new neighbors, winning again for the same reason. This was repeated until the entire cluster died."
blog_name = "indirect"
format = "markdown"
tags = [ ]
summary = "One of my favorite bugs in this class from an actual system was in a ring-based storage system where nodes could do health..."
can_like = false
is_blazed = false
can_blaze = false
interactability_blaze = "everyone"
can_send_in_message = true
can_reply = false
display_avatar = true
type = "quote"
id_string = "149270751043"
date = "2016-08-21 14:20:52 GMT"
state = "published"
id = 1.49270751043e+11
is_blaze_pending = false
post_url = "https://indirect.tumblr.com/post/149270751043/one-of-my-favorite-bugs-in-this-class-from-an"
slug = "one-of-my-favorite-bugs-in-this-class-from-an"
can_reblog = false
is_blocks_post_format = false
timestamp = 1.471789252e+09
note_count = 0.0
interactability_reblog = "everyone"
reblog_key = "8HXgnmTK"
short_url = "https://tmblr.co/ZY3jby2B1EkT3"
should_open_in_legacy = true
source = "<a href=\"http://danluu.com/concurrency-bugs/##One+of+my+favorite+bugs+in+this+class+from+an+actual+system+was+in+a+ring-based+storage+system+where+nodes+could+do+health+checks+on+their+neighbors+and+declare+that+their+neighbors+should+be+dropped+if+the+health+check+fails.+One+node+went+bad%2C+dropped+all+of+its+storage%2C+and+started+reporting+its+neighbors+as+bad+nodes.+Its+neighbors+noticed+that+the+bad+node+was+bad%2C+but+because+the+bad+node+had+dropped+all+of+its+storage%2C+it+was+super+fast+and+was+able+to+report+its+good+neighbors+before+the+good+neighbors+could+report+the+bad+node.+After+ejecting+its+immediate+neighbors%2C+to+bad+node+got+new+neighbors+and+raced+the+new+neighbors%2C+winning+again+for+the+same+reason.+This+was+repeated+until+the+entire+cluster+died.\">Notes on concurrency bugs</a>"

[tumblr.blog]
uuid = "t:PgyUJU3SA2Klwyt81UWAwQ"
updated = 1.738205153e+09
can_show_badges = true
name = "indirect"
title = "indirect"
description = ""
url = "https://indirect.tumblr.com/"

[tumblr.blog.tumblrmart_accessories]

[tumblr.reblog]
comment = "<p><a href=\"http://danluu.com/concurrency-bugs/##One+of+my+favorite+bugs+in+this+class+from+an+actual+system+was+in+a+ring-based+storage+system+where+nodes+could+do+health+checks+on+their+neighbors+and+declare+that+their+neighbors+should+be+dropped+if+the+health+check+fails.+One+node+went+bad%2C+dropped+all+of+its+storage%2C+and+started+reporting+its+neighbors+as+bad+nodes.+Its+neighbors+noticed+that+the+bad+node+was+bad%2C+but+because+the+bad+node+had+dropped+all+of+its+storage%2C+it+was+super+fast+and+was+able+to+report+its+good+neighbors+before+the+good+neighbors+could+report+the+bad+node.+After+ejecting+its+immediate+neighbors%2C+to+bad+node+got+new+neighbors+and+raced+the+new+neighbors%2C+winning+again+for+the+same+reason.+This+was+repeated+until+the+entire+cluster+died.\">Notes on concurrency bugs</a></p>"
tree_html = ""
+++
