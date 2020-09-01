# Trying out the Netlify CMS

## Thoughts

The "out of the box" experience is pretty great. CMS for a static site! There's a big open question though:

> How would this project fare without Netlify?

I set up using one of their starters and the experience was just as smooth as one would hope. However, the CMS does require a back end and the example uses Netlify's "Identity" service as a back end. It also uses some sort of Netlify-Github integration.

So...

- How difficult would it be to set this up with a standalone static site?
- How difficult or easy would the backend be to maintain? (Assuming you're not using a SaaS as the backend)
  - Could one just use github users / roles as the backend?
- How would one handle forms?
- What is the intended use of cloud functions?

  - Maybe it's for handling forms, but I'm not sure.

### Conclusion?

A very cool project, however, without further research it's unclear how useful it would be without Netlify as SaaS provider.

## Notes

Be sure to set this in your `config.yml`:

```sh
publish_mode: editorial_workflow
```

For your own site it wouldn't matter actually, but for a collaboration with a team this is quite useful. It allows the whole editorial review process with a custom UI in the admin area.
