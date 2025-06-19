# autohost

Make this self-contained commit: https://github.com/dimacurrentai/autohost/commit/dbd21a6f2b03a910ef4b1231cdc7e2384339df8b

---

To enable auto-deployment to `github.io`, set the option to `GitHub Actions` under `Settings` -> `Pages`:

![image](https://github.com/user-attachments/assets/8ddb4b61-2172-4025-9061-306e25d61ede)

You may need to re-run the action manually.
 
---

Observe https://dimacurrentai.github.io/autohost/.

---

To test locally:

```
(cd rust-wasm; cargo install wasm-pack)
(cd rust-wasm; wasm-pack build --target web)
python3 -m http.server
```
