- name: Conectar ao Tailscale
  uses: tailscale/github-action@v4
  with:
    authkey: ${{ secrets.TAISSCALE_AUTH_KEY }}
