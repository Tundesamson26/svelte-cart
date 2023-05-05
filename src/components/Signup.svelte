<script>
  import "@appwrite.io/pink";
  import "@appwrite.io/pink-icons";
</script>

  <section>
    <div
      class="card u-cross-center u-width-full-line u-max-width-400"
      style="margin: 40px auto"
    >
      <form method="post" class="form u-margin-block-start-24">
        <ul class="form-list">
          <li class="form-item">
            <!-- svelte-ignore a11y-label-has-associated-control -->
            <label class="label">Email</label>
            <div class="input-text-wrapper">
              <input
                type="email"
                class="input-text u-padding-inline-end-56"
                placeholder="Email address"
                name="email"
              />
            </div>
          </li>
          <li class="form-item">
            <!-- svelte-ignore a11y-label-has-associated-control -->
            <label class="label">Password</label>
            <div class="input-text-wrapper">
              <input
                type="password"
                class="input"
                placeholder="Password"
                name="password"
              />
            </div>
          </li>
          <li class="form-item">
            <!-- svelte-ignore a11y-label-has-associated-control -->
            <label class="label">Confirm Password</label>
            <div class="input-text-wrapper">
              <input
                type="password"
                class="input"
                placeholder="Confirm password"
                name="password"
              />
            </div>
          </li>
        </ul>

        <div class="form-footer">
          <div class="u-flex u-main-end u-gap-12">
            <button class="button" type="submit">Signup</button>
          </div>
        </div>
      </form>
    </div>
  </section>

