//test42

- name: Setup tmate session
  if: always()
  uses: mxschmitt/action-tmate@v3
  timeout-minutes: 15
