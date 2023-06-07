# next.js-antd-select
Fixing styling issue in Next.js with Antd

When you use `Select` component from Ant.d, sometimes the dropdown doesn't get closed.
To fix that issue, please check `next.config.js`.
If you set `reactStrictMode` as `true`, remove it from the config.
The `Select` component should work.
