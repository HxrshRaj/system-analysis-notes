## Problem
Transactional apps often face unstable network conditions which can interrupt user flows.

## Observations
- Users retry actions without knowing system state
- Network delays cause duplicate or failed requests

## Approaches Considered
1. Strict online validation
2. Offline-first local caching with delayed sync

## Trade-offs
- Offline-first improves reliability
- Requires reconciliation logic to handle conflicts

## Conclusion
Offline-first designs improve user trust when paired with clear feedback mechanisms.

## Limitations
Delayed confirmations can confuse users if UI is not designed carefully.
