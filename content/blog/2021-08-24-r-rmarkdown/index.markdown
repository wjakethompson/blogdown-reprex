---
title: "Example Rmarkdown Post"
author: "Jake Thompson"
date: 2021-08-24T21:13:14-05:00
---



# Unnumbered equation

Here is an unnumbered equation:

```
$$
a^2 + b^2 = c^2
$$
```

$$
a^2 + b^2 = c^2
$$


# Numbered equation

```
$$
\begin{equation}
  a^2 + b^2 = c^2
  (\#eq:pythag)
\end{equation}
$$
```

$$
`\begin{equation}
  a^2 + b^2 = c^2
  \tag{1}
\end{equation}`
$$

# Numbered equation - no line break

```
$$\begin{equation}
  a^2 + b^2 = c^2
  (\#eq:pythag2)
\end{equation}$$
```

`$$\begin{equation}
  a^2 + b^2 = c^2
  (\#eq:pythag2)
\end{equation}$$`
