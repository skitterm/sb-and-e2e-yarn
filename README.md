To reproduce the success:

1. Run `yarn` (I'm using yarn 4.9.1)
1. Observe that Storybook (standalone) is still on `8.6.12`, whereas Storybook (via `@chromatic-com/playwright`)'s storybook is on `9.0.0-rc.0`
1. Attempt to upgrade Storybook (standalone)'s to 9.x (`yarn dlx storybook@next upgrade`)
1. Observe the upgrade indicates it's upgrading from `8.6.12` to `9.0.0-rc.0`
1. Observe the upgrade fails
