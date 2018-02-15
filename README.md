![Tabletop Tracker](http://www.tabletoptracker.com/images/tabletop-tracker-large.png "Table Top Tracker")

[TabletopTracker.com](http://www.tabletoptracker.com/) tracks which new board games deserve your attention among the thousands of games that are published each year.

Rankings are based on the number and quality of user ratings on [BoardGameGeek.com](http://boardgamegeek.com/). Data is calculated daily. Hover over the title of a chart for more details.

Tabletop Tracker was created and is maintained by [Nathan T. Baker](http://nathantbaker.com/). Subscribe to the [Tabletop Tracker email list](http://eepurl.com/ctZUa5) to learn when new charts and features are added.

## Local Development

### Prerequisites

1. Install [Elm](http://elm-lang.org/).
1. Install [Sass](https://sass-lang.com/).

### To boot up this app locally

1. Clone this repo.
1. In the root folder, run `elm make` to download dependencies.
1. Run `elm reactor`.
1. Visit [http://localhost:8000/index.html](http://localhost:8000/index.html).

### Scripts

- To compile Sass into CSS run `sass --watch sass/style.scss:css/style.css`.