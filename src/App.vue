<template>
  <div>

    <App_Property_Type></App_Property_Type>

    <!--<App_Property_Selected></App_Property_Selected>-->

    <!--<App_Add_Photos></App_Add_Photos> -->

    <!--<App_Add_Project></App_Add_Project>-->

    <!--<App_Property_Amenities></App_Property_Amenities>-->

    <!--<App_Property_detail></App_Property_detail>-->

    <!--<App_Listing_Detail></App_Listing_Detail>-->

    <!--<App_Listing_Detail2></App_Listing_Detail2>-->
  </div>
</template>



<script>

  import Add_photos from './component/add_photos.vue';
  import Add_Project from './component/add_project.vue';
  import Listing_Detail from './component/listing_details.vue';
  import Listing_Detail_2 from './component/listing_details_2.vue';
  import Property_detail from './component/property_detail.vue';
  import Property_Amenities from './component/property_detail.amenities.vue';
  import Property_Type from './component/property_type.vue';
  import Property_Type_selected from './component/property_type_selected.vue';

  export default {

      components: {
          App_Add_Photos: Add_photos,
          App_Add_Project:Add_Project,
          App_Listing_Detail:Listing_Detail,
          App_Listing_Detail2:Listing_Detail_2,
          App_Property_detail:Property_detail,
          App_Property_Amenities:Property_Amenities,
          App_Property_Type:Property_Type,
          App_Property_Selected:Property_Type_selected
      }
  }

</script>

<style>



</style>
