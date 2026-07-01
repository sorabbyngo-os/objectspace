# ObjectSpace Architecture

## Overview

ObjectSpace is the native object runtime of Sorabbyngo OS.

It replaces the traditional application-centric interaction model with an object-centric computing model where users manipulate intelligent digital objects instead of applications and files.

ObjectSpace sits directly beneath Chameha and AION and above the system capability layer. It serves as the bridge between human intent and system execution.

Unlike conventional desktop environments, ObjectSpace is not a graphical shell. It is a runtime responsible for creating, managing, relating, synchronizing, projecting, and executing digital objects throughout the operating system.

The Linux filesystem remains fully available through the compatibility layer for legacy applications and developers. ObjectSpace becomes the preferred runtime for AI-native applications and interactions.

---

# Vision

Traditional operating systems revolve around applications.

Sorabbyngo revolves around intent.

Instead of asking:

"Which application should I open?"

the user simply expresses intent:

- Continue my work.
- Design a logo.
- Summarize yesterday's meeting.
- Share this with James.
- Project this on the wall.
- Resume coding.

ObjectSpace converts these intents into executable object operations.

---

# Core Principles

## Everything is an Object

Every entity inside Sorabbyngo is represented as an intelligent object.

Examples include:

- Documents
- Photos
- Videos
- Conversations
- AI Tasks
- Browser Sessions
- Terminal Sessions
- Projects
- Devices
- Workspaces
- Memories
- Notifications
- Contacts

Objects possess identity, relationships, permissions, history, context, and lifecycle.

---

## Intent Before Interface

Users interact with AION instead of applications.

ObjectSpace receives structured intent from AION and determines which objects must be created, modified, synchronized, or projected.

Applications become implementation details rather than the primary interface.

---

## Spatial Computing

Objects can exist beyond screens.

They may be:

- Grabbed
- Dropped
- Thrown
- Pulled
- Projected
- Shared
- Duplicated
- Organized

These interactions remain consistent regardless of the underlying hardware.

---

## Persistent Context

Object relationships persist across sessions.

Projects remember:

- documents
- conversations
- browser tabs
- reminders
- meetings
- collaborators

The operating system remembers work instead of merely remembering files.

---

## Local First

All object operations execute locally whenever possible.

Cloud resources are optional enhancements rather than requirements.

---

## Privacy by Design

Objects remain under user ownership.

Synchronization occurs only between trusted devices.

Encryption and policy enforcement are delegated to CML and Sentinel.

---

# Position within Sorabbyngo

                User
                  │
            Natural Intent
                  │
         Chameha + AION
                  │
            ObjectSpace
     ┌────────┼─────────┐
     │        │         │
 Byngox   Byngonet     HAL
     │        │         │
      Sorabbyngo Core
              │
      Sorabbyngo Kernel
              │
 Linux Compatibility Layer
              │
           Hardware

---

# Responsibilities

ObjectSpace is responsible for:

- Spatial Object Model
- Object lifecycle
- Workspace management
- Context management
- Session continuity
- Projection management
- Gesture abstraction
- Spatial interaction
- Object relationships
- Rendering abstraction
- Shared workspaces
- Cross-device object continuity

ObjectSpace is NOT responsible for:

- AI reasoning (Byngox)
- Networking (Byngonet)
- Hardware control (HAL)
- Security enforcement (Sentinel)
- Safety policies (CML)

---

# Long-Term Goal

ObjectSpace transforms computing from an application-driven experience into an intent-driven experience.

Rather than navigating software, users naturally manipulate intelligent digital objects while AION orchestrates the required capabilities behind the scenes.

ObjectSpace serves as the runtime that enables this transition and becomes the primary interaction model for future generations of Sorabbyngo OS.
