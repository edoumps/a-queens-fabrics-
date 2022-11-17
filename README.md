African Queens Fabrics (a-queens-fabrics)

An online store app dedicated to African fabrics.

App Features

Models

      - Product

                Attributs:

                :title(string)
                :image_1(string)
                :image_2(string)
                :image_3(string)
                :image_4(string)
                :image_5(string)
                :price(integer)
                :is_featured(boolean_false)
                :collection_date(string)
                :description(text)
                :is_sold_out(boolean_false)

      - Order

Controllers

      @pages_controller
      @products_controller
      @carts_controller
      @orders_controller

Views

      pages/home.html.erb
      products/index.html.erb
      products/show.html.erb
      carts/show.html.erb
      orders/new.html.erb
      orders/show.html.erb

Gems

    * active_admin
    * carrierwave
    * mini_magick
    * active_link_to
    * simple_form
