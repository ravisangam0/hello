# SD Digital Hub

Premium digital agency website with Vercel Speed Insights integration.

## Features

- Responsive web design
- Supabase integration for data management
- Vercel Speed Insights for performance monitoring

## Development

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
npm install
```

### Building Speed Insights

The Speed Insights bundle is pre-built, but if you need to rebuild it:

```bash
npm run build:analytics
```

This command bundles the Vercel Speed Insights code into `speed-insights.bundle.js`.

## Deployment

Deploy this site to Vercel for automatic Speed Insights integration:

1. Push to your repository
2. Connect to Vercel
3. Deploy
4. Enable Speed Insights in your Vercel dashboard

Once deployed, Speed Insights will automatically track Web Vitals and performance metrics.

## Speed Insights

This project uses [@vercel/speed-insights](https://vercel.com/docs/speed-insights) to monitor:

- First Contentful Paint (FCP)
- Largest Contentful Paint (LCP)
- First Input Delay (FID)
- Cumulative Layout Shift (CLS)
- Time to First Byte (TTFB)
- Interaction to Next Paint (INP)

Data will be visible in the Vercel dashboard after deployment and user traffic.
