# fizzbuzz
A simple fizzbuzz exercise

## Screening Frontend
### Wireframe:
<img src="https://user-images.githubusercontent.com/8353990/120715828-8ed17a00-c49b-11eb-82bb-eb9cc8d8bcd2.png" width="400" />

### Definitions:
<ol>
        <li>
          <strong>Create a list component</strong>
          <ul>
            <li>
              This component should be able to render a list of items consumed
              from Mercado Livre public API 
            </li>
            <li>
              Create a service that get the items from the ML public items API.
              <ul>
                <li>https://api.mercadolibre.com/sites/MLB/search?q=cards</li>
                <li>Limit the amount of items to 15</li>
                <li>Use this service to populate the list component.</li>
                <li>Implement some sort of cache strategy.</li>
              </ul>
            </li>
            <li>
              The user should be able to select an item clicking on it and
              indicate (some way) it's selected.
            </li>
            <li>
              The component should be able to set the row background depending
              on the item order.
            </li>
            <li>If the item is a multiple of 3 the row should be yellow.</li>
            <li>If the number is a multiple of 5 the row should be red.</li>
            <li>
              If the number is a multiple of 3 and 5 the row should be orange.
            </li>
          </ul>
        </li>
      </ol>
