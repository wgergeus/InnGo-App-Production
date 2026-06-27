# InnGo App

<p align="center">
  <img src="src/assets/images/logo.svg" alt="InnGo" width="180">
</p>

> **InnGo App** is the hotel-side Property Management System (PMS) of the InnGo platform.
> It is designed to run locally inside the hotel and provides day-to-day hotel operations.

---

# Current Status

**Current Version:** Development Preview

The current release is built and tested on:

- Raspberry Pi 3
- ARM64 Architecture (aarch64)
- Raspberry Pi OS Lite (64-bit)

The application currently runs as a standalone binary and uses a `.env` file for configuration.

> **Note**
>
> There is currently **no setup/install wizard**.
> Configuration is performed manually through the `.env` file.
> A complete setup script and installer will be added in future releases.

---

# Current Modules

The current version includes:

- Front Office
- Administration

Additional modules will be added in upcoming releases.

---

# Requirements

- Raspberry Pi 3 (ARM64)
- Raspberry Pi OS Lite (64-bit)
- MariaDB Server
- Nginx

---

# Default Installation Directory

The recommended installation directory for linux is:

```text
/opt/inngo/
```

After setting up the application, your deployment directory `/opt/inngo/` (or `C:\inngo\` on Windows) should look like this:
