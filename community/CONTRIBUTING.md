Publishing a world to MythosArc Community
For creators — three steps
Export your world. In MythosArc: Library → Worlds → your world's ⋯ menu → Export. That downloads one self-contained .mythosarc-world.json file that already contains the premise, cast, lorebook, openings, cover image and character portraits.

Sign in to GitHub (free account) and open this repository.

Submit it. Either:

Easy: open an Issue titled World: <your world name> and attach the file, or
Direct: use Add file → Upload files into community/worlds/, then edit community/worlds.json to add your entry (see below).
A maintainer reviews it and merges. Once merged, it appears in the app's Community tab for everyone.

For the maintainer — the index
worlds.json at the repo root of community/ lists every published world:

json


{
  "worlds": [
    {
      "id": "example-world",
      "title": "Example World",
      "author": "your-github-name",
      "genre": "Whatever genre it is",
      "description": "One sentence about what makes this world interesting.",
      "download": "https://raw.githubusercontent.com/USERNAME/REPO/main/community/worlds/example-world.mythosarc-world.json",
      "thumb": "https://raw.githubusercontent.com/USERNAME/REPO/main/community/worlds/example-world.webp"
    }
  ]
}
Replace USERNAME and REPO with your repository, and the three example values with your world's real ones. The id is any unique slug you pick.

All fields are optional except title and download. Missing thumb shows a plain cover; the app never breaks on a missing field.

What is checked before merge
the file opens as a MythosArc world export
it has a title, a premise, and a cover image
it is not a duplicate of an existing entry
the content follows the repository's content rules
Content policy
Submissions must be the creator's own work. By submitting you confirm you made the world and you allow it to be hosted here and downloaded through the app. Worlds can be removed at any time at the maintainer's discretion.
