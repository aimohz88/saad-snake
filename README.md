# حيّه

A phone snake game where the snake is a name. The player types any Arabic name (up to 12 letters, default سعد). Each thing the snake eats goes down its body as a lump, and when the lump reaches the tummy the name stretches with a tatweel: محمد → محمـد → محـمـد → مـحـمـد.

The tatweels are spread over every gap where the two letters join (not after ا د ذ ر ز و ة). A name with no such gap, like داود, stretches from its start: ـداود.

The snake glides smoothly between cells, and its jaws open when food is just ahead.

Play: https://saad-snake.netlify.app

Everything is in `index.html`.

Pushing to `main` deploys automatically to Netlify.
