# tip-feedback

Private, encrypted delivery of individual student feedback for **The Invisible Pen**.

Every report in `f/` is encrypted in the browser with AES-256-GCM (PBKDF2, 310k iterations)
before it is ever committed. This repository never contains readable feedback — only
ciphertext plus a small password screen. Passwords are delivered to each reader privately
and are not stored anywhere in this repo.

Pages are marked `noindex` and are not linked from anywhere public.
