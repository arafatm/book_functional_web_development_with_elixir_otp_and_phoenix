# Functional Web Development with Elixir, OTP, and Phoenix

https://pragprog.com/book/lhelph/functional-web-development-with-elixir-otp-and-phoenix

**Part 1**, Define the Functional Core in Elixir

We’ll begin with only the most basic elements of Elixir—data structures, functions, and modules.

In Chapter 2, Model Data and Behavior, we’ll use data structures to
model our domain entities. We’ll define functions that work with these data
structures to establish the business logic of the game. We’ll also define
modules to organize these functions and keep the code legible and easy to
maintain.

In Chapter 3, Manage State with a State Machine, we’ll build a
purely functional finite state machine to manage the game over time and enforce
the rules. We’ll proceed the same way we did in Chapter 2, with a data
structure, multiple clauses of a single function, and a module to hold them
all.  

**Part 2**, Add OTP for Concurrency and Fault Tolerance

This is where we’ll introduce OTP to provide concurrency, parallelism, and
fault tolerance.

In Chapter 4, Wrap It Up in a GenServer, we’ll build a GenServer
module to contain the business logic and state machine we built in Part 1.
You’ll learn how to spawn a new, long-lived process from this GenServer for
each pair of players. That process will hold the state for their game as well
as provide an interface to interact with it.

In Chapter 5, Process Supervision for Recovery, we’ll explore how to
make our game resilient to failures large and small. We’ll build a supervisor
to watch over each game process and restart it if it crashes. You’ll also see
how to restore a game process’s state after a crash and even after the whole
BEAM, Erlang’s virtual machine, crashes or restarts.  

**Part 3**, Add a Web Interface with Phoenix

With all the work we’ve done in the previous two parts, we’ll finally be ready
to build a web interface with Phoenix.

In Chapter 6, Generate a New Web Interface with Phoenix we’ll create a new
Phoenix project. You’ll learn how OTP applications let us seamlessly integrate
our work from the first two parts into this new Phoenix project as a
dependency. Then we’ll explore how we can call into that earlier work directly
from different Phoenix components.

In Chapter 7, Create Persistent Connections with Phoenix Channels, we’ll focus
on the stateful, persistent connections that Phoenix provides called channels.
You’ll learn how to use JavaScript functions in a browser to communicate
directly over a channel with a specific game process on the server. We’ll also
explore how to use Phoenix Presence to keep track of which players are actually
playing an individual game.

### Online Resources

- https://pragprog.com/titles/lhelph/source_code
- https://pragprog.com/titles/lhelph/errata
- https://pragprog.com/titles/lhelph/release_info

## 1. Mapping Our Route

Data structures, functions, and modules.

### Lay the Foundation with Elixir
### Add a Web Interface with Phoenix
### Functional Web Development
### The Game of Islands
### Part I. Define the Functional Core in Elixir

## 2. Model Data and Behavior

### The Benefits
### Let’s Build It
### Discover the Entities and Model the Domain
### Transforming Data
### Putting the Pieces Together
### Wrapping Up

## 3. Manage State with a State Machine
### A Quick Look at State
### A Bit of History
### State Machines
### A Functional State Machine for Islands
### Working Through the States
### Wrapping Up
### Part II. Add OTP for Concurrency and Fault Tolerance

## 4. Wrap It Up in a GenServer
### A Look at Micro-Services
### OTP Solutions
### Getting Started with GenServer
### Initializing GenServer State
### Customizing GenServer Behavior
### Naming GenServer Processes
### Wrapping Up

## 5. Process Supervision for Recovery
### Fault Tolerance
### Linking Processes
### Introducing the Supervisor Behaviour
### Supervision Strategies
### The Child Specification
### A Supervisor for the Game
### Starting the Supervision Tree
### Starting and Stopping Child Processes
### Putting the Pieces Together
### Recovering State After a Crash
### Wrapping Up
### Part III. Add a Web Interface with Phoenix

## 6. Generate a New Web Interface with Phoenix
### Frameworks
### Applications
### Generate a New Phoenix Application
### Adding a New Dependency
### Call the Logic from the Interface
### Wrapping Up

## 7. Create Persistent Connections with Phoenix Channels
### The Beauty of Channels
### The Pieces That Make a Channel
### Let’s Build It
### Establish a Client Connection
### Converse Over a Channel
### Connect the Channel to the Game
### Phoenix Presence
### Authorization
### Wrapping Up

## A1. Installing System Dependencies
### Elixir
### Erlang
### Phoenix
### Node.js and NPM
### Bibliography
