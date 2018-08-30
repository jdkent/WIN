# Writing Initiative for Neuroscience

This will currently just be a simple place to find all the (electronic) resources shared at the meetings.

## Schedule of Events

|    Date    |      Speaker     |          Topic          | Submitting Author(s) | Lead Reviewer(s) |
|:----------:|:----------------:|:-----------------------:|:--------------------:|:----------------:|
| 2018-08-28 |  Krystal Parker  |      Grantsmanship      |     Banu & Maria     |  Stacey & Rachel |
| 2018-09-18 | Colleen Campbell |    Science Engagement   |     McCall & Gail    |   Vicky & Banu   |
| 2018-10-23 |    Eric Taylor   |      Grantsmanship      |    Kelsey & Stacey   |  Benton & Frida  |
| 2018-11-27 |  Matt Gilchrest  |  Research Communication |      Ben & Vicky     |  Maria & McCall  |
| 2019-01-29 |   Mark Blumberg  | Popular Science Writing |    Frida & Benton    |  Kelsey & James  |
| 2019-02-19 |        TBA       |           TBA           |     Tien & Rachel    |        Lex       |
| 2019-03-19 |        TBA       |           TBA           |      Lex & James     |    Ben & Gail    |
| 2019-04-19 |        TBA       |           TBA           |          TBA         |       Tien       |

## Posts/Resources

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>