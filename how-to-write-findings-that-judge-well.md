## How to write findings that judge well
A strong finding is not just about being correct. It also needs to be easy to trust, easy to follow, and easy to evaluate.

1. **Lead with confirmed behavior**  
   Start with what was reproduced or directly observed before moving into theory.

2. **Separate confirmed behavior from likely root cause**  
   Judges are more receptive when the report clearly distinguishes proof from explanation.

3. **Make preconditions explicit**  
   If a finding depends on narrow assumptions, say so clearly instead of hiding them.

4. **Do not overclaim severity**  
   A well-defended Medium usually performs better than an aggressive High with weak justification.

5. **Explain why this is not just governance or ops**  
   If a privileged actor is involved, show why the behavior is still a real protocol issue.

6. **Reduce reviewer effort**  
   A clean repro, a concrete impact path, and precise wording all help the finding judge better.

7. **Use protocol language when possible**  
   Tie the issue back to stated invariants, intended flows, or documented guarantees.

8. **Prefer technical clarity over dramatic tone**  
   Strong reports sound grounded, not theatrical.
