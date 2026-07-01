# Spatial Object Model (SOM)

## Overview

The Spatial Object Model (SOM) is the foundational abstraction of ObjectSpace.

Traditional operating systems organize information as files stored inside directories.

Sorabbyngo OS organizes information as intelligent objects existing inside a persistent object space.

Files become only one possible representation of an object.

Applications become capabilities that operate on objects rather than the primary interface through which users access information.

---

# Philosophy

Unix introduced:

Everything is a file.

Sorabbyngo introduces:

Everything is an Object.

Objects can represent:

- Documents
- Images
- Audio
- Video
- Browser Sessions
- Conversations
- AI Tasks
- Projects
- Devices
- Workspaces
- Memories
- Contacts
- Notifications
- Services
- Digital Twins

Each object possesses its own identity, history, relationships, permissions, lifecycle and context.

---

# Object Identity

Every object receives a globally unique Object ID.

Example:

ObjectID:
obj://workspace/project/8af4d2...

Object IDs never depend on filenames.

Objects may have multiple representations while preserving the same identity.

---

# Object Components

Every object contains:

Metadata

- Object ID
- Type
- Owner
- Creation time
- Last modification
- Version
- Security classification

Content

The actual payload.

Examples:

PDF

Image

Conversation

Workspace

3D model

Executable capability

Relationships

Objects may connect to:

Projects

People

Devices

Meetings

Memories

Tasks

Policies

Capabilities

Context

Objects understand where they belong.

Examples:

Current workspace

Active project

Current room

Nearby devices

Current conversation

Permissions

Objects maintain independent permissions independent of storage location.

History

Objects retain lineage.

Who created it.

Who modified it.

Where it travelled.

Which devices accessed it.

---

# Object Categories

Content Objects

Documents

Media

Notes

Presentations

Spreadsheets

Executable Objects

Capabilities

Workflows

Automation

AI plans

Context Objects

Meetings

Projects

Research

Coding sessions

Device Objects

Phones

Laptops

Displays

Projectors

IoT devices

People Objects

Users

Digital twins

Teams

Organizations

Memory Objects

Conversation history

Knowledge

Relationships

AI memory

Workspace Objects

Desktop layouts

Coding sessions

Creative environments

Meeting environments

---

# Object Lifecycle

Objects progress through predictable stages.

Created

↓

Active

↓

Shared

↓

Projected

↓

Archived

↓

Restored

↓

Deleted

Deletion removes visibility.

History remains recoverable according to system policy.

---

# Relationships

Objects form a graph instead of a directory tree.

Example

Research Project

├── Meeting

├── Conversation

├── Presentation

├── Browser Session

├── Terminal Session

├── Dataset

└── AI Summary

The user navigates relationships rather than folders.

---

# Object Mobility

Objects may move between

devices

workspaces

rooms

users

projection surfaces

without changing identity.

Movement preserves history.

---

# Object Synchronization

Synchronization occurs through Byngonet.

ObjectSpace determines:

what changed

what relationships changed

which permissions changed

Byngonet only transports the updates.

---

# Object Intelligence

Objects are not passive.

They expose capabilities.

Example

Research Project

can answer:

Continue work

Summarize changes

Find related files

Open latest notebook

Project onto wall

Share with engineering

The intelligence comes from AION and Byngox.

ObjectSpace stores and manages the object.

---

# Compatibility

Legacy applications continue reading and writing files.

ObjectSpace maps filesystem entries to object representations.

This allows existing Linux software to operate without modification while enabling AI-native experiences.

---

# Long-Term Vision

The Spatial Object Model replaces the traditional file-centric view of computing with an object-centric ecosystem where relationships, intent and context become first-class citizens.

Every subsystem within Sorabbyngo OS communicates through intelligent objects, making ObjectSpace the universal runtime shared by the entire platform.
