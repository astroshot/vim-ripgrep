# vim-ripgrep

    :Rg <string|pattern>

Word under cursor will be searched if no argument is passed to `Rg`

## configuration


| Setting                | Default                   | Details
| -----------------------|---------------------------|----------
| g:rg\_binary           | rg                        | path to rg
| g:rg\_format           | %f:%l:%c:%m               | value of grepformat
| g:rg\_command          | g:rg\_binary --vimgrep    | search command
| g:rg\_highlight        | false (0)                 | true (1) if you want matches highlighted
| g:rg\_derive\_root     | false (0)                 | true (1) if you want to find project root from cwd
| g:rg\_root\_types      | ['.git']                  | list of files/dir found in project root
| g:rg\_window\_location | botright                  | quickfix window location

## misc

Show root search dir

    :RgRoot
