this.handlerAdapter
- RequestMappingHandlerAdapter
- HttpRequestHandlerAdapter
- SimpleControllerHandlerAdapter

ModelAndView mv 반환 
- view
- model
- status
- cleared


jsp 파일 반환하는 경우 <br>
mv != null, mv.view : jsp 파일명
jstlView

문자열 반환하는 경우 <br>
mv = null

ResponseEntity를 반환하는 경우 <br>
mv = null

;...

DispatcherServlet#processDispatchResult
DispatcherServlet#render

ViewResolverComposite#resolveViewName
