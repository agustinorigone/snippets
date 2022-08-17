## Pre-condition
Sample file: conversion_rates_fetcher_daemon.service

## Start
systemctl start conversion_rates_fetcher_daemon

## Restart
systemctl restart conversion_rates_fetcher_daemon

## Status
systemctl status conversion_rates_fetcher_daemon

## Start on Boot
systemctl enable conversion_rates_fetcher_daemon

## Disable Start on Boot
systemctl disable conversion_rates_fetcher_daemon

## Edit (on-the-fly)
systemctl edit conversion_rates_fetcher_daemon --full

## Logs (default)
/var/log/journal conversion_rates_fetcher_daemon.service.log
