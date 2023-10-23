Emacs dot-ticker-mode
=====================

Emacs minor-mode to display current Polkadot price on the mode-line.

Installation
------------

Your .emacs file should looks like:

    (require 'dot-ticker)

    ;;Optional: You can setup the fetch interval
    ;;default: 10 secs
    (setq dot-ticker-api-poll-interval 10)

    ;;Enable dot-ticker-mode
    (dot-ticker-mode 1)
