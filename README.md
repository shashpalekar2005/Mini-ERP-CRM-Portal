# Mini ERP + CRM Operations Portal

A modern, full-stack wholesale and distribution operations portal built with Node.js, Express, TypeScript, PostgreSQL (Prisma ORM), React 18, Vite, and Vanilla CSS.

## Monorepo Structure

```
mini-erp-crm/
├── backend/            # Express + TypeScript + Prisma API server
│   ├── prisma/         # Database schema & migrations
│   ├── src/            # Controllers, routes, middleware, services
│   └── package.json
├── frontend/           # React + Vite + TypeScript SPA
│   ├── src/            # Components, pages, context, api, styles
│   └── package.json
├── package.json        # Workspace root package configuration
└── README.md
```

## Features
- **Authentication & RBAC**: JWT-based login for Admin, Sales, Warehouse, Accounts roles.
- **Customer CRM**: Manage leads, contacts, follow-up notes & dates.
- **Product Inventory**: SKU tracking, current stock, low stock alert thresholds, stock movement audit log.
- **Sales Challans**: Dynamic challan generator, stock locking transaction, customer & product snapshots.
- **Reports & PDF**: Export invoice/challan as PDF.
- **Docker Ready**: Full docker-compose stack for local development and deployment.
