# TV Remote

A phone remote for my Android TV: play/pause, seek, volume, history and watch later.
The page talks to the TV through the public ntfy.sh relay. Every message is end-to-end encrypted (AES-GCM)
with a key derived from the remote code shown on the TV, so the relay only sees ciphertext. No code or key is
stored in this repository.
