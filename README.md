🎱 Snooker Tournaments Manager

A clean and efficient Laravel-based application for creating, managing, and tracking snooker tournaments, duels, and player rankings.

This project is built to handle complete tournament workflows — from creating contestants and scheduling duels, to automatically updating rankings and browsing tournaments with pagination.
Admins have full control through an authentication-protected dashboard, while regular visitors can freely view tournaments, rankings, and match results.

🚀 Features
🏆 Tournament Management

Create, update, and delete snooker tournaments

Associate duels with tournaments

Paginated tournament overview

Admin-only actions protected by authentication

🎮 Duel System

Create duels manually with custom contestant names

Option to temporarily store duels in Laravel Cache before saving

Update or delete duels as needed

Support for tournament-based duel grouping

👤 Contestant & Ranking System

Full CRUD for contestants (admin only)

64-player ranking system

Rankings displayed on the frontend with sorting

Contestants not directly tied to tournaments (decoupled design)

🔐 Authentication & Admin Controls

Admin-only access for all creation/update/delete actions

Single admin user system

Hidden login button for non-admin visitors

Secure logout functionality

🖼️ UI & Frontend

Blade components for ranking cards and tournament views

Image carousel support for tournament pages

Responsive layout optimized for mobile & desktop

🧱 Tech Stack

Laravel 10

PHP 8.1+

Blade templates

MySQL

Laravel Cache for temporary duel storage

🎯 Purpose of the Project

This app is designed as a practical, structured solution for managing snooker competitions while experimenting with:

Pivot tables for tournament–duel relationships

Pagination, eager loading, and best practices

Clean controller separation (Show, Create, Update, etc.)

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>
