# ASP.NET Core Sales and CRM Platform

Smart CRM is a self-hosted sales and customer relationship management platform built on ASP.NET Core MVC 10 and SQL Server, for small and mid-sized businesses that want to run sales without renting a subscription CRM. Contacts and Accounts link together with duplicate detection, CSV import/export, and full activity timelines, while Leads convert through a guided workflow straight into Contacts, Accounts, and Deals. A drag-and-drop Kanban board manages the pipeline across admin-configurable stages, with win/loss tracking built in. Custom fields, role-based access, and a live dashboard round out the Phase 1 build, with the complete six-phase blueprint included for future growth. It ships as unencrypted source code — one-time price, white-label ready, no domain restrictions.

<img src="https://www.coderobotics.com/frontend/assets/icon/smart-crm-sales-pipeline-source-code.jpg">

Smart CRM is a self-hosted sales and customer relationship management platform built with ASP.NET Core MVC 10 and SQL Server, for small and mid-sized businesses that want to run their sales process without renting it from a subscription vendor. This listing covers Phase 1: authentication & roles, Contacts & Accounts, Leads, and a full Deals/Pipeline Kanban board — with the complete six-phase blueprint included for future build-out.

Contacts & Accounts Companies and contacts linked together, with duplicate detection on create, CSV import with a duplicate-review preview step, tagging, custom fields, and a full activity timeline.
Lead Management Source tracking and manual scoring, with a guided Convert workflow that turns a Lead into a Contact plus an optional Account and Deal in one step.
Deals & Pipeline A drag-and-drop Kanban board across admin-configurable pipelines and stages, with win/loss tracking and a required loss reason so nothing closes without context.
Custom Fields Text, Number, Date, Dropdown, Checkbox, or Multiline fields on any entity — Account, Contact, Lead, or Deal — added through the UI, no code changes required.
Role-Based Access Super Admin, Sales Manager, Sales Rep, and Support roles, with row-level data visibility enforced automatically.
Live Dashboard Open pipeline value, deals won this month, leads this month, a pipeline-by-stage chart, and a recent activity feed — scoped to whoever's signed in.
The Core Differentiator: Configurable, Not Hard-Coded
 
Pipelines, stages, and fields live in admin-managed data, not in the codebase — so the sales process can change without a redeploy.

Super Admins create pipelines and add/edit/delete/reorder stages at will
A generic custom-fields engine (EAV-style) drives dynamic fields across all four entities from one shared editor
Row-level data scoping runs entirely off signed-in user claims — no database lookup in the authorization path
CSV imports stage to GUID-named files, never a client-supplied path, closing off path traversal
Deal attachments store outside wwwroot and serve only through an authenticated download action
Tech Stack
 
Layer	Technology
Framework	ASP.NET Core MVC 10 (.NET 10)
Database	SQL Server
ORM	Entity Framework Core 10, code-first
Auth	ASP.NET Core Identity — role-based, custom claim for row-level scoping
UI	Bootstrap 5.3, Bootstrap Icons — vendored, no CDN dependency
Kanban	SortableJS
Charts	Chart.js
CSV Import/Export	CsvHelper
Modules
 
Dashboard · Accounts · Contacts · Leads · Deals · Pipelines & Stages (Admin) · Custom Fields (Admin) · Users (Admin)

Roles & Permissions
 
Role	Access
Super Admin	Full access to all data and admin screens (Pipelines, Custom Fields, Users)
Sales Manager	Full CRM access — own records plus direct reports' records
Sales Rep	Full CRM access — own records only
Support	Read-only Contacts and Accounts; no Lead or Deal access
Who Smart CRM Makes Sense For
 
Developers and agencies who want a ready-made CRM to white-label and resell to their own clients
Growing businesses that have outgrown a spreadsheet or a fixed-feature subscription CRM and want a system they can shape around their own pipeline
Business owners who want to own their data outright, in their own SQL Server database, rather than inside a vendor's account
Anyone tired of per-user pricing who would rather pay once and add users freely
FAQ
 
1. Is Smart CRM really a one-time purchase? 
Yes. Smart CRM is sold as a one-time-license source code product — no recurring subscription, no per-user fees.

2. What's included in this listing versus the full blueprint? 
This listing includes Phase 1, fully built: auth & roles, Contacts/Accounts, Leads, and the Deals/Pipeline Kanban board. The complete Smart CRM Blueprint document is included, detailing five further phases — Activities & Calendar, Email Integration, an Automation/Workflow Engine, Reporting, and an API/Webhooks layer.

3. Can I resell Smart CRM to my own clients? 
Yes. Smart CRM ships with white-label rights and no domain restrictions, making it suitable for developers and agencies to rebrand and resell.

4. Do I need to know how to code to use Smart CRM? 
No. It runs like any CRM out of the box. Coding knowledge only matters if you want to customize it or add the later blueprint phases yourself.

5. Is Smart CRM multi-tenant? 
No — it's single-tenant by design, which keeps setup, hosting, and support simple for one business or one client deployment at a time.

Licensing: Own It Outright — No Subscriptions, No Lock-In
 
Unencrypted ASP.NET Core MVC source, white-label rights
One-time price — no recurring subscription
No domain or installation restriction
Single-tenant design keeps setup and support simple
Includes the Smart CRM Blueprint document covering all six planned phases

More details and download link:
https://www.coderobotics.com/product/asp.net-core-sales-and-crm-platform
