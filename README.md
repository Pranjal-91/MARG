# MARG
Developed a Medical Management Application (MediManage) to simplify pharmacy inventory management, medicine billing, and invoice generation. The application allows users to add and manage medicines, search inventory with auto-suggestions, issue medicines, and generate invoices with QR code support for digital payments. 

## Deployment

This is a static HTML application with no dependencies to install or build step.
`netlify.toml` disables the build command and publishes the repository root,
overriding the previous dashboard settings (`make all` and `public`). A rewrite
serves `Medi.html` at `/`, while `/Medi.html` remains accessible directly.
The functions directory is set to `netlify/functions` instead of the stale
`my_medi` setting; the application currently has no server functions.
