# حيّه

A phone snake game where the snake is a name. The player types any Arabic name (up to 12 letters, default سعد). Each thing the snake eats goes down its body as a lump, and when the lump reaches the tummy the name stretches with a tatweel: محمد → محمـد → محـمـد → مـحـمـد.

The tatweels are spread over every gap where the two letters join (not after ا د ذ ر ز و ة). A name with no such gap, like داود, stretches from its start: ـداود.

The snake glides smoothly between cells, and its jaws open when food is just ahead. Losing plays a taunt: a voice line (يا غشيم، يا سعد…) followed by a cartoon laugh.

Play: https://aimohz88.github.io/saad-snake/

Everything is in `index.html`; the taunt clips are in `sounds/`. The laughs (`laugh-*.mp3`) are from [Mixkit](https://mixkit.co/free-sound-effects/laugh/) under the Mixkit free sound-effects licence; the voice lines were made with the Windows Arabic (Saudi) voice.

Pushing to `main` publishes to GitHub Pages within a minute. (The old Netlify copy at saad-snake.netlify.app also deploys on push, but only while that account has credits.)
