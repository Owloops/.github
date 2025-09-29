<div align="center">

<pre style="text-align: left; display: inline-block; font-size: 10px; line-height: 1.4; letter-spacing: 0.5px; color: #ff6c19;">
 o
...        ...............     ....
...o    .........................
 ...............................
  ...............oo.........ooo..
      .......ooooooooooo..o.   .o.
  .........oooo         oo       .
 .........ooo
 ........ooo      ooo         oo
 ........oo.    ooooooo      o
 ........oo     ooooooo
 ........oo.    ooooo       ooo
  ........oo     ooooo     ooooo
   ........o.               o.
    ........oo
      ..........
        ..................
             ..........
</pre>

<h3>Owloops</h3>

<p><strong>CLI tools that work</strong></p>

<p><a href="https://github.com/owloops">GitHub</a> • <a href="https://discord.gg/aFrPHspzzs">Discord</a> • <a href="https://www.youtube.com/@owloops">YouTube</a></p>

</div>

## Projects

<table>
<tr>
<td width="50%">

**[updo](https://github.com/Owloops/updo)**

Website monitoring with real-time alerts across 13 AWS regions. Integrates with Prometheus/Grafana and supports webhook notifications.

```bash
brew install owloops/tap/updo
updo monitor https://example.com
```

</td>
<td width="50%">

**[claude-powerline](https://github.com/Owloops/claude-powerline)**

Statusline for Claude Code. Tracks usage costs, tokens, git status, and session metrics in real-time.

```bash
npm install -g @owloops/claude-powerline
```

</td>
</tr>
<tr>
<td width="50%">

**[flyo](https://github.com/Owloops/flyo)**

Deploy self-hosted applications to Fly.io. Pre-configured for popular open-source tools with automated GitHub Actions.

```bash
git clone git@github.com:owloops/flyo.git
make deploy app=glance
```

</td>
<td width="50%">

**[cdko](https://github.com/Owloops/cdko)**

AWS CDK orchestrator. Deploy stacks across multiple accounts and regions with pattern matching and parallel execution.

```bash
npm install -g @owloops/cdko
cdko -p MyProfile -s MyStack -r us-east-1,eu-west-1
```

</td>
</tr>
</table>

## Archived

<table>
<tr>
<td width="50%">

**[flybird](https://github.com/owloops/flybird)**

Replay browser tests exported from Chrome DevTools Recordings.

*Archived 2024 - LLMs made test generation more efficient than recordings*

</td>
<td width="50%">

**[chrome-recorder](https://github.com/owloops/owloops-chrome-recorder)**

Export Chrome DevTools recordings to Owloops test format.

*Archived 2024 - AI-powered test writing superseded recording workflows*

</td>
</tr>
</table>
