# Map

 نوع البيانات Map ويتم تسميته Dictionary في لغات البرمجة الأخرى. وهو عبارة عن مفتاح وقيمة.


    void main() {
    
      // declare an Map
       var infoPublic = {"CourseN":"Flutter Course","time":"3 weeks"};
       Map infoCourses = {"CourseN":"Dart & flutter Course","ID":1000293,"time":"3 weeks"};
       Map<String,String> details = {"CourseN":"Dart & flutter","totalStudent":"20"};
    
     // print the values Map 
       print(infoPublic);
       print(infoCourses);
       print(details);
    }


المخرجات :


    {CourseN: Flutter Course, time: 3 weeks}
    {CourseN: Dart & flutter Course, ID: 1000293, time: 3 weeks}
    {CourseN: Dart & flutter, totalStudent: 20}

