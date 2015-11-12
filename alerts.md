# Alerts

> This feature is currently under active development, and not yet available in the interface.

Alerts are a way to warn the administrator about various events. The first kind of alerts will be emails and also a dedicated in `xo-web` to display them.

## Performances alerts

The administrator will configure alerts based on performance thresholds.

The configurable metrics are:

* CPU usage (VM, host)
* RAM usage (VM, host)
* network bandwidth (VM, host)
* load average (host)
* disk IO (VM)
* total IO (SR, only for XenServer Dundee)

If any configured values exceed the threshold during a selection period of time, an alert will be sent.

## Updates alerts

When your XOA detects new packages, you'll be notified by email.

## Backup alerts

Same story for backups: when a backup failed, you'll receive an email.

You will also choose to be notified only if it fails or even after each backup job.