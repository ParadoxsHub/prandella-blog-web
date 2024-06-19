<template>
  <div class="container container-fluid">
    <div class="row">
      <div class="col info">
        <button type="button" class="btn">基本按钮</button>
      </div>
      <div class="col">
        <button
          type="button"
          class="btn btn-outline-primary ms-2"
          data-bs-toggle="modal"
          data-bs-target="#m1"
        >
          主要按钮
        </button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-secondary ms-2">
          次要按钮
        </button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-success ms-2" disabled>
          成功
        </button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-info ms-2">信息</button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-warning ms-2">警告</button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-danger ms-2">危险</button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-dark ms-2">黑色</button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-light ms-2">浅色</button>
      </div>
      <div class="col">
        <button type="button" class="btn btn-outline-link ms-2">链接</button>
      </div>
    </div>
  </div>
  <dl class="row">
    <dt class="col-sm-3">Description lists</dt>
    <dd class="col-sm-9">A description list is perfect for defining terms.</dd>
    <dt class="col-sm-3">Term</dt>
    <dd class="col-sm-9">
      <p>Definition for the term.</p>
      <p>And some more placeholder definition text.</p>
    </dd>

    <dt class="col-sm-3">Another term</dt>
    <dd class="col-sm-9">
      This definition is short, so no extra paragraphs or anything.
    </dd>

    <dt class="col-sm-3 text-truncate">Truncated term is truncated</dt>
    <dd class="col-sm-9">
      This can be useful when space is tight. Adds an ellipsis at the end.
    </dd>

    <dt class="col-sm-3">Nesting</dt>
    <dd class="col-sm-9">
      <dl class="row">
        <dt class="col-sm-4">Nested definition list</dt>
        <dd class="col-sm-8">
          I heard you like definition lists. Let me put a definition list inside
          your definition list.
        </dd>
      </dl>
    </dd>
  </dl>
  <div class="row">
    <div class="col-3"></div>
    <div class="col-6">
      <div class="mb-3">
        <label for="exampleFormControlInput1" class="form-label">
          Email address
        </label>
        <input type="email" class="form-control" placeholder="n@ex.com" />
      </div>
      <div class="mb-3">
        <label for="exampleFormControlTextarea1" class="form-label">
          Example textarea
        </label>
        <textarea class="form-control" id="i2" rows="3"></textarea>
      </div>
    </div>
    <div class="col-3"></div>
  </div>

  <div class="row">
    <div class="col-3"></div>
    <div class="col-6">
      <select class="form-select" aria-label="Default select example">
        <option selected>Open this select menu</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>
    <div class="col-3">
      <label for="customRange1" class="form-label">Example range</label>
      <input type="range" class="form-range" id="customRange1" />
    </div>
  </div>

  <div class="row">
    <div class="col-3"></div>
    <div class="col-6">
      <form class="row g-3">
        <div class="col-md-6">
          <label for="inputEmail4" class="form-label">Email</label>
          <input type="email" class="form-control" id="inputEmail4" />
        </div>
        <div class="col-md-6">
          <label for="inputPassword4" class="form-label">Password</label>
          <input type="password" class="form-control" id="inputPassword4" />
        </div>
        <div class="col-12">
          <label for="inputAddress" class="form-label">Address</label>
          <input type="text" class="form-control" id="a1" placeholder="北京" />
        </div>
        <div class="col-12">
          <label for="inputAddress2" class="form-label">Address 2</label>
          <input type="text" class="form-control" id="a2" placeholder="昌平" />
        </div>
        <div class="col-md-6">
          <label for="inputCity" class="form-label">City</label>
          <input type="text" class="form-control" id="inputCity" />
        </div>
        <div class="col-md-4">
          <label for="inputState" class="form-label">State</label>
          <select id="inputState" class="form-select">
            <option selected>Choose...</option>
            <option>...</option>
          </select>
        </div>
        <div class="col-md-2">
          <label for="inputZip" class="form-label">Zip</label>
          <input type="text" class="form-control" id="inputZip" />
        </div>
        <div class="col-12">
          <div class="form-check">
            <input class="form-check-input" type="checkbox" id="gridCheck" />
            <label class="form-check-label" for="gridCheck">
              Check me out
            </label>
          </div>
        </div>
        <div class="col-12">
          <button type="submit" class="btn btn-primary">Sign in</button>
        </div>
      </form>
    </div>
    <div class="col-3"></div>
  </div>

  <div class="spinner-grow text-primary" role="status">
    <span class="visually-hidden">Loading...</span>
  </div>
  <div class="spinner-grow text-secondary" role="status">
    <span class="visually-hidden">Loading...</span>
  </div>
  <div class="spinner-grow text-success" role="status">
    <span class="visually-hidden">Loading...</span>
  </div>
  <div class="spinner-grow text-danger" role="status">
    <span class="visually-hidden">Loading...</span>
  </div>
  <div class="spinner-grow text-warning" role="status">
    <span class="visually-hidden">Loading...</span>
  </div>
  <div class="spinner-grow text-info" role="status">
    <span class="visually-hidden">Loading...</span>
  </div>
  <div class="spinner-grow text-light" role="status">
    <span class="visually-hidden">Loading...</span>
  </div>
  <div class="spinner-grow text-dark" role="status">
    <span class="visually-hidden">Loading...</span>
  </div>

  <!-- Modal -->
  <div
    class="modal fade"
    id="m1"
    tabindex="-1"
    aria-labelledby="model-label"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h1 class="modal-title fs-5" id="ml1">Modal title</h1>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">HelloWorld</div>
        <div class="modal-footer">
          <button
            type="button"
            class="btn btn-secondary"
            data-bs-dismiss="modal"
          >
            Close
          </button>
          <button type="button" class="btn btn-primary">Save changes</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class HomeView extends Vue {}
</script>
