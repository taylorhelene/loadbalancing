## use autocannon to monitor requests that can be handled


┌─────────┬────────┬─────────┬─────────┬─────────┬────────────┬────────────┬─────────┐
│ Stat    │ 2.5%   │ 50%     │ 97.5%   │ 99%     │ Avg        │ Stdev      │ Max     │
├─────────┼────────┼─────────┼─────────┼─────────┼────────────┼────────────┼─────────┤
│ Latency │ 315 ms │ 5133 ms │ 9722 ms │ 9845 ms │ 5080.96 ms │ 2867.64 ms │ 9845 ms │
└─────────┴────────┴─────────┴─────────┴─────────┴────────────┴────────────┴─────────┘
┌───────────┬────────┬────────┬─────────┬─────────┬────────┬───────┬────────┐
│ Stat      │ 1%     │ 2.5%   │ 50%     │ 97.5%   │ Avg    │ Stdev │ Min    │
├───────────┼────────┼────────┼─────────┼─────────┼────────┼───────┼────────┤
│ Req/Sec   │ 5      │ 5      │ 7       │ 9       │ 6.9    │ 1.05  │ 5      │
├───────────┼────────┼────────┼─────────┼─────────┼────────┼───────┼────────┤
│ Bytes/Sec │ 3.4 kB │ 3.4 kB │ 4.77 kB │ 6.13 kB │ 4.7 kB │ 711 B │ 3.4 kB │
└───────────┴────────┴────────┴─────────┴─────────┴────────┴───────┴────────┘

Req/Bytes counts sampled once per second.
# of samples: 10

200 requests in 10.1s, 47 kB read
31 errors (31 timeouts)