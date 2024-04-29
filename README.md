# Customized build of st - the simple (suckless) terminal

The [suckless terminal (st)](https://st.suckless.org/) with some additional patches.

## Branches

+ **master** - unchanged base.
+ **conf.01** - base + [Vim Browse](https://st.suckless.org/patches/vim_browse/) + [boxdraw](https://st.suckless.org/patches/boxdraw/) + [glyph wide support](https://st.suckless.org/patches/glyph_wide_support/) + [xresources](https://st.suckless.org/patches/xresources/).
+ **conf.02** - base + [font2](https://st.suckless.org/patches/font2/) + [xresources](https://st.suckless.org/patches/xresources/) + [scrollback](https://st.suckless.org/patches/scrollback/) (doesn't use a ring buffer + column and row reflow + scrolling using Shift+MouseWheel + changing how fast the mouse scrolls)
+ **conf.03** - base + [Vim Browse](https://st.suckless.org/patches/vim_browse/) + [CSI 22, 23](https://st.suckless.org/patches/csi_22_23/) + [colorschemes](https://st.suckless.org/patches/colorschemes/) + [cyclefonts](https://st.suckless.org/patches/cyclefonts/) + [glyph wide support](https://st.suckless.org/patches/glyph_wide_support/).
+ **conf.XX.X** - parent conf.XX branch + config.h.

