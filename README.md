# WordPress SQLite Console Plugin

⚠️ **EXPERIMENTAL USE ONLY** - This plugin is intended for local development environments only. Do not use in production.

This plugin provides a SQL console interface for WordPress developers. It enables direct database access for debugging and plugin development.

This was used with sqlite-database-integration plugin.But it can be used with any database.

## Features

- Execute SQL queries directly from WordPress admin
- View table structures
- Browse and search database contents
- Test queries during plugin development

## Benefits for Developers

1. **Rapid Prototyping** - Quickly test database queries during plugin development
2. **Debugging** - Inspect database state when troubleshooting issues
3. **Learning** - Understand WordPress database structure through direct interaction
4. **Performance Analysis** - Test and optimize queries before implementing in code

## Installation

1. Upload the plugin to your `/wp-content/plugins/` directory
2. Activate the plugin through the WordPress admin
3. Access the console under Tools → SQLite Console

## Usage

The SQLite console provides a web-based interface to:

- Execute SELECT, INSERT, UPDATE, DELETE queries

## Security Notes

- Access is restricted to administrators only
- Consider deactivating on production sites

This tool is designed specifically for developers working with WordPress, providing the database access needed to build and test new functionality efficiently.