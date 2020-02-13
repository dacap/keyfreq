HOW TO USE IT?
==============

Include the following lines in your `.emacs` file:

    (require 'keyfreq)
    (keyfreq-mode 1)
    (keyfreq-autosave-mode 1)

And use `keyfreq-show` to see how many times you used a command.

How to exclude commands?
========================

    (setq keyfreq-excluded-commands
          '(self-insert-command
            forward-char
            backward-char
            previous-line
            next-line))
