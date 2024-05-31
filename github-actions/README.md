# github-actions

## Job outputs

### Multiline outputs

```bash
echo 'multiline_output<<EOF' >> $GITHUB_OUTPUT
echo "${multiline_var}" >> $GITHUB_OUTPUT
echo 'EOF' >> $GITHUB_OUTPUT
```