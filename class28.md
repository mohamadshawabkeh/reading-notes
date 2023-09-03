# API Integration

## Query String vs. Path Parameters

- **Query String Parameter:** Query string parameters are additional pieces of information appended to a URL after a "?" symbol. They are typically used for filtering, sorting, or providing optional data to an API. For example, `http://our-site.com/api/resource?param=value`.

- **Path Parameter:** Path parameters are variables embedded within the URL path itself, typically denoted by placeholders enclosed in curly braces. They are used to define the structure of a resource's URL. For example, `http://our-site.com/api/resource/{id}`.

## Constructing API URLs

To construct an API URL with a path id parameter based on the provided information:

- Domain: `http://our-site.com`
- API Version: `v3`
- Model Name: `stuff`
- ID: `things`

The API URL would be: `http://our-site.com/v3/stuff/things`

## Dynamic Interfaces

We've created a dynamic API with an "interface." Here's a non-technical explanation of how it works:

Imagine the interface as a universal remote control for your favorite gadgets. Instead of having a separate remote for each device, you have one magical remote that can adapt to control any gadget. This dynamic interface in our API is like that magical remote.

When you send a request to our API, it uses this interface to understand what you want to do. It's like telling the remote, "I want to watch TV now." The remote then magically transforms its buttons and functions to match your TV, so you can change channels, adjust the volume, and more.

Similarly, our API's dynamic interface adapts to your request. Whether you're asking for information about "stuff" or "things," the interface figures out how to get that data for you. It's like having a versatile remote control for your data, making everything super easy!

## Authentication Server Build

To build an authentication server, you'd typically create a secure service that manages user identities and permissions. This server helps ensure that only authorized users can access certain resources or perform specific actions.

## Middleware for Authentication

Middleware is like a bouncer at the entrance of a club. It checks your ID and decides if you're allowed inside. In the world of APIs and authentication:

- **Basic Authentication:** Think of it as showing your ID card to the bouncer. You provide your username and password with each request, and the middleware checks if they match what's in its list. If yes, you get access.

- **Bearer Authentication:** Here, you have a special stamp on your hand that proves you're allowed in. You show the stamp (a token) with your request, and the middleware checks if it's valid. If it is, you're in!

## OAuth Handshake

OAuth is like asking a friend to vouch for you to get into a private party. Here's how it works:

1. **You (the App):** You want access to someone else's party (their data or services).

2. **The Party Host (Resource Owner):** They control the party and have the guest list.

3. **Your Friend (OAuth):** You ask your friend to talk to the host for you. Your friend says, "Hey, my buddy wants to come in."

4. **Party Host (Resource Owner) Talks to Your Friend (OAuth):** The host asks your friend if they trust you. If yes, they give your friend a special key (access token).

5. **Your Friend (OAuth) Gives You the Key (Access Token):** Now, you have the key to get into the party (access token). You show it at the door, and they let you in.

6. **Access Granted:** You're inside the party (you have access to the resource). Your friend (OAuth) made it happen!

## Role-Based Access Control (RBAC)

RBAC is like giving people different levels of access in a video game:

- **Player (User):** This is you, the gamer. You have certain abilities and restrictions.

- **Roles (Classes):** Think of these as different character classes in the game. Each role has unique powers and limitations.

- **Permissions (Skills):** Abilities or skills that come with your role. Some players can heal, some can attack, and some can't do either.

- **Role Assignment (Character Creation):** When you start the game, you choose a character class (role). This determines your abilities.

- **Access Control (Game Rules):** The game's rules make sure you can't do things your character class isn't allowed to do. Wizards can't wear heavy armor, for example.

 ### return to [Main Read Me File](./README.md)