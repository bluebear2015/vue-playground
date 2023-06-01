<template>
  <div class="expression-exercises container">
    <div class="row">
      <div class="col-12">
        <h1>Exercises</h1>
        <div class="border p-1">
          <p>
            Write a math equation Vue can evaluate, inside of the curly braces
            below:
          </p>

          <p>{{2+2 * 123 / 4}}</p>
        </div>
        <div class="border p-1">
          <p>
            {{ 'hello world' }}
          </p>
          <p>{{}}</p>
        </div>
      </div>
    </div>
  </div>
</template>