# Static Website Hosting Using Docker on a Virtual Machine

## Project Overview
This project demonstrates how a static website can be hosted using Docker containers inside a Linux virtual machine.
The objective is to understand virtualization and containerization concepts used in modern server environments.

The project uses a Type-2 hypervisor to create a virtual machine, inside which Docker will be installed
to deploy a containerized Nginx web server hosting a static website.

## Technologies Used
- Windows (Host OS)
- Type-2 Hypervisor (VirtualBox / VMware)
- Ubuntu Server (Virtual Machine)
- Docker
- Nginx Web Server
- HTML, CSS
- Cloudflare Tunnel

## Project Objectives
- To understand virtual machine setup using a hosted hypervisor
- To deploy Docker inside a virtual machine
- To host a static website using Docker containers
- To study virtualization and container integration

## Documentation
- Project overview: `docs/project-overview.md`
- System architecture: `docs/architecture.md`
- Virtual machine setup: `docs/vm-setup.md`
- VM networking configuration: `docs/vm-networking.md`
- Cloudflare Tunnel setup: `docs/cloudflare-tunnel.md`

## Development Phases
- Phase 1: Planning and repository initialization ✔
- Phase 2: Virtual machine setup ✔
- Phase 3: Docker installation and testing
- Phase 4: Static website development
- Phase 5: Dockerization of the website
- Phase 6: Networking and access configuration
- Phase 7: Documentation and analysis
- Phase 8: Final testing and submission

## Project Status
Phase 2 completed. Ubuntu Server virtual machine has been successfully set up and configured.