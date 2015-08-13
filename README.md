# Psych objects reports

- `$ TEST_UNIT=1 bundle exec derailed exec perf:objects`
- `$ TEST_UNIT=10 bundle exec derailed exec perf:objects`
- `$ TEST_UNIT=100 bundle exec derailed exec perf:objects`

![compare sheet](https://cloud.githubusercontent.com/assets/1000669/9244422/9c8d58dc-41cd-11e5-8eb4-b5cd2a3cced1.png)

from above sheet can see that `ruby-2.2.2/lib`, `redis-3.2.1`, `newrelic_rpm-3.12.1.298` has memory leaks.

--

- Rails 4.2.3
- Ruby 2.2.2p95
