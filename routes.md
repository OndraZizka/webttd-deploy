---
layout: default
title: Routes
description: Create reusable transport plans and assign vehicles to run them.
permalink: /routes/
kicker: Manage the service, then scale the fleet
lead: A route is a shared service plan: define its stops once, then assign vehicles to carry it out.
---

## One plan, multiple vehicles

In WebTTD, a route is separate from any one vehicle. It stores an ordered sequence of compatible stops for a transport
mode. Assign one or more matching vehicles to the route, then manage the service from the shared plan. When demand grows,
you can add vehicles to increase capacity instead of manually maintaining a different stop list on every bus or train.

## Create a route

1. Build the stops or stations first. A route can only use stops that match its mode: road, rail, water, or air.
2. Open **Routes** on the toolbar. Give the route a name, choose its mode, select its first two stations, and choose
   **Create route**.
3. For a longer route, open the relevant vehicle toolbar menu—such as **Road vehicles** or **Trains**—then open its mode-
   specific route list and choose **New route**. Add and order the stops, then save the route.
4. Open a compatible vehicle and choose **Assign a route**. Select the route and choose **Assign this route**. Repeat for
   each vehicle that should provide the service.
5. Start the vehicles. The **Routes** manager lists the vehicles assigned to each route and lets you start, stop, or
   unassign them individually.

## Change the service without micromanaging the fleet

Edit the shared route when you need to change its ordered stops. Stopped vehicles assigned to it receive the updated plan;
running vehicles adopt new stops when they reach a stop that remains on the edited route. An active trip is not
teleported or abruptly cancelled.

A vehicle can still receive individual Go To orders when you need a special trip. Editing its individual orders detaches
it from the shared route after confirmation, so the rest of the fleet continues following the common plan.

Routes also check infrastructure access. If a service uses roads, rail, or stations owned by another company, choose the
available access or rental terms before relying on that part of the route.
