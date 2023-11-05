# Nginx Tutorial - Session 03: Basic Architecture of Nginx
- Video of this Session: [Link](https://www.youtube.com/watch?v=I_Qul4thJMU&list=PL63NzugBawGe1nUhAveIBfYHtbiXvKKEb&index=3) 

Welcome to Session 03 of the Nginx Persian Tutorial, where we'll explore the basic architecture of Nginx .

- **Vahag Gragoosian**
  - DevOps Enthusiast
  - GitHub: [Vahag's GitHub](https://github.com/Vahaggn)
  - LinkedIn: [Vahag's LinkedIn](https://www.linkedin.com/in/vahag-gragosian/)
  - Youtube Channel: [Vahag's Youtube](https://www.youtube.com/@vahaggn) 

## Table of Contents

1. [Nginx Process](#nginx-process)
   - [Master and Worker](#master-and-worker)
     - [Count of Workers](#count-of-workers)
     - [Connection Handling](#connection-handling)
2. [Nginx Commands](#nginx-commands)
   - [Basic Commands](#basic-commands)
   - [Useful Switches](#useful-switches)
     - [-h](#-h)
     - [-v](#-v)
     - [-V](#-V)
     - [-t](#-t)
     - [-T](#-T)
     - [-s](#-s)
   - [Additional Commands](#additional-commands)
     - [reload](#reload)
     - [stop](#stop)
     - [quit](#quit)
     - [reopen](#reopen)
3. [Nginx Config Files](#nginx-config-files)
   - [Blocks](#blocks)
   - [End with ;](#end-with-;)

## Nginx Process

### Master and Worker

Nginx operates with a master process that manages multiple worker processes. These workers handle incoming connections.

#### Count of Workers

The number of worker processes can be configured according to your server's resources.

#### Connection Handling

Nginx effectively handles client connections, serving web content, and other tasks.

## Nginx Commands

### Basic Commands

Nginx provides several basic commands to control its operation.

### Useful Switches

Nginx commands can be augmented with switches for specific functionality.

#### -h

Get Nginx help.

#### -v

Get Nginx version.

#### -V

Get Nginx version and compile options.

#### -t

Test Nginx configuration.

#### -T

Test Nginx configuration and dump it to the standard output.

#### -s

Signal Nginx processes.

### Additional Commands

Nginx also supports other commands for various purposes.

#### reload

Reload the configuration file without stopping Nginx.

#### stop

Stop Nginx processes fast.

#### quit

Perform a graceful shutdown of Nginx processes.

#### reopen

Reopen log files without restarting Nginx.

## Nginx Config Files

Nginx configuration files consist of various blocks, each serving a different purpose.

- Blocks: `server`, `http`, `stream`, `location`, and more.
- Configuration statements end with a semicolon (;).