<template>
  <CRow>
    <CCol md="12">
      <CCard>
        <CCardBody>
          <CForm>
            <CInput
              label="*Email:"
              placeholder="Email"
              horizontal
              :value="chrisvenue.email"
              v-model="chrisvenue.email"
            />
            <CInput
              label="Website:"
              placeholder="Website"
              horizontal
              :value="chrisvenue.website"
              v-model="chrisvenue.website"
            />
            <CInput
              label="Facebook URL:"
              placeholder="Type Facebook URL"
              horizontal
              :value="chrisvenue.facebookurl"
              v-model="chrisvenue.facebookurl"
            />
            <CInput
              label="Instagram URL:"
              placeholder="Type Instagram URL"
              horizontal
              :value="chrisvenue.instagramurl"
              v-model="chrisvenue.instagramurl"
            />
            <CInput
              label="YouTube URL:"
              placeholder="Type YouTube URL"
              horizontal
              :value="chrisvenue.youtubeurl"
              v-model="chrisvenue.youtubeurl"
            />
            <CInput
              label="Twitter URL:"
              placeholder="Type Twitter URL"
              horizontal
              :value="chrisvenue.twitterurl"
              v-model="chrisvenue.twitterurl"
            />
          </CForm>
        </CCardBody>
      </CCard>
    </CCol>
  </CRow>
</template>

<script>
import { db } from "./../../firebase.js"
export default {
  name: 'CDetailsInternet',
  props: {
    chrisvenue: Object
  },
  methods: {

  }
}
</script>
