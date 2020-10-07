+++
# Introduce the blog.
widget = "starter.blog.intro"
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 10  # Order that this section will appear in.

title = "✏️ Blog Template"
subtitle = "For [Academic Website Builder](https://sourcethemes.com/academic/)"

[design.background]
  # Background color.
  color = "#090a0b"

  # Text color (true=light or false=dark).
  text_color_light = true
+++

widget = "people"  # Use the People widget
headless = true  # This file represents a page section.

# ... Put Your Section Options Here (title etc.) ...

[content]
  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
  user_groups = ["Organizers",
                 "Mentors",
                 "Team",
                 "Sponsors",
                 "Visitors"]

[design]
  # Show user's social networking links? (true/false)
  show_social = false

  # Show user's interests? (true/false)
  show_interests = true
