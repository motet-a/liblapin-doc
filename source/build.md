
# Compilation #

Les exemples fonctionnent si la liblapin est installée correctement.

## Compiler avec une real_install ##

La ligne de compilation à utiliser après une real_install est la suivante :

```sh
gcc *files* -L/usr/local/lib/ -llapin -lsfml-audio -lsfml-graphics -lsfml-window -lsfml-system -lstdc++ -ldl -lm
```

Vous pouvez évidemment la modifier selon vos besoins. (Rajouter le -lmy par exemple)
