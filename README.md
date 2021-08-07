Steps
1. go to `lsp3.py`, enable lsp-mode, go to line 9 -> `gd`
2. it jumps to `lsp2.py`, go to line 7 -> `gd`
3. it jumps to `lsp1.py`.
4. use `better-jumper-jump-backward` / `lsp-ui-peek-jump-backward` to jump back.

Note: you might need to try second time. The backward stacks are same for the first time.

backward stack for `better-jumper-jump-backward` (C-o):
1. lsp1.py line 3
2. lsp2.py line 7
3. lsp2.py line 6
4. lsp3.py line 9

backward stack for `lsp-ui-peek-jump-backward`:
1. lsp1.py line 3
2. lsp2.py line 7
4. lsp3.py line 9
