# Kinematics

A standalone browser app for visualizing constant-acceleration schoolbook
kinematics:

- `a(t) = a0`
- `v(t) = V0 + a0t`
- `x(t) = x0 + V0t + 0.5a0t^2`

Open `index.html` directly in a browser, or serve the folder locally:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Then open `http://127.0.0.1:4173/`.

The displayed time range is `0..20 s`.
